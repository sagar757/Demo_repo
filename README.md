GIT INIT# Hello Sagar again, after http
Still learning and never accomplishing any bigger target,
learn more and keep building more
# Hello Sagar again, after http
Still learning and never accomplishing any bigger target,
learn more and keep building more


## SubHeader
open folder git 
then git clone https://github.com/sagar757/Demo_repo.git
after cloning edited the file
was practing on VisualStudio Code on my Laptop
git status command
create a new  file with name with index.html
that is still untracked
use " git add . " or use " git add file_name" to track
to commint 
use git commit -m "added index.html" -m "some description"
-m stand for message

git commit is to save the file locally 

**************""Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'Admin@DESKTOP-BDPM812.(none)')"
that was the error because the havent setup the email id

to set up

git config --global user.email "kyouremail.id"

save changes.

***********************************************************************************************************
To push the save the changes to github online use gitbash to generate ssh key using below command

use ssh account setup
ssh-keygen -t rsa -b 4096 -C "kltechnology.recruit@gmail.com"

once it generate check using ls | grep testkey

cat testkey to see the content of teh generate file
paste the content on the github account in the setting ssh key
ssh-add ~/.ssh/privatefilename
ssh -T git@github.com to verify succesfully login using git bash 

but on visual studio code error came as permission denied (public key)

try using ssh -vT git@github.com


**************************************************************************




 push the changes to github online

git push master origin
will not work


*************************************************


Try 

Maybe you just need to commit. I ran into this when I did:

mkdir repo && cd repo
git remote add origin /path/to/origin.git
git add .
Oops! Never committed!

git push -u origin master
error: src refspec master does not match any.
All I had to do was:

git commit -m "initial commit"
git push origin main
Success!
*********************************************************
<<<<<<< HEAD
pbcopy < ~/vsgitbash.pub

step 
with new file not clone from github
git init
git status
git add .
git commit -m "some description" -m "somedescription"
git remote add origin git@github.com:sagar757/ledand-buzzer.git
git remote -v
git push origin master


ssh connection
ssh connection
eval "$(ssh-agent -s)" // start the ssh agent
ssh-add ~/.ssh/testkey  // load the private key to ssh agent
ssh -T git@github.com  //connect to the websit
=======
start ssh agent use 
eval "$(ssh-agent -s)"
ssh-add ~/.ssh/testkey
ssh -T git@github.com
**********************************************************
git add .
git commit
git status
git init



>>>>>>> aa8a2efbac860074c597c541f90be29ad284dd89
