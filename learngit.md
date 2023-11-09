 This txt is for git-learning. I will try to record as most as I can to complete this file. :)
# Day1
## Install Git and config your username and email
1. Install:  I try to use git in Ubuntu18.04, so I only have to run sudo apt-get git.
2.  Config:
git config --global user.name="caosiyu"
git config --global user.email="caosiyu0807@gmail.com"
## To build a repository in Git
1. 建立一个空目录
mkdir learngit
cd learngit
pwd
2. Turn it into a repository
git init
3. Add a file to the git repository
   1. git add learngit.md
   2. git commit -m "This is a file for git-learning"
4. QA
   1. Why we need two steps for adding a file?
   We can commit many files at one time as long as they are all added to the repository.
   2. We should notice that git init must be run in the git repository.

## To modify a file
1. Try to see the  status of our file.
git status
2. Try to see what is modified


