# hesham-github

this is testing Git hub

## This is test

### This is another test

#### THis is another test

---

# diagram from (local repo) to (remote repo)

## working directory => staging area => local repo => remote repo

From working directory You write (git add) to put it in staging area
From staging area You write (git commit) to put it in local repo
From local repo You write (git push) to put it in remote repo

From remote repo You write (git fetch) to put it in local repo
from local repo You write (get directory) to put it in working directory
From local repo You write (get merge) to put it in working directory

---

# inside terminal

---

## git clone https://blablabla (You take the link from Git hub )

Now you build it, So let's work to make other of the team see it

## git status shows you what files exists in the working directory

these files existed and untracked

## git add \*

this to add all files untracked

## git add images/ index.html css/

this to add 3 files that untracked
After every time you write (git add something) you write (git status) to make sure

## git reset head images/

This means you will make un added means untracked like the first status it was
So when you want to write git add \* (All files) except one file you will undo this only file by (git reset head css/)
After finishing make sure by (git status)

---

Note: termenal asked me to write my name so I wrote
(git config --global user.email "heshamabdelzim3@gamil.com" )
Note: imagine you forgot something for example you want to add new excel sheet. So after adding you wrote (git status)
it will give you that there is one file untracked. So you write (git add excel) then (git status) You will find there is 2 commits

---

## git commit -m "we did new feature and did well"

the output of that command (3 files changed)

## git remote -v

this gives you => origin https://github.com/heshamabdelazim/hesham-github.git
origin is the remote name

## git branch

it gives you => main ..............ETC
to see all branches in the local
every branch has features, For example branch name called main or master

## git push origin main

this command to push all files you (added) to your account on Git-hub
but what is (origin) and (main)? they are like this (git push remoteName branchName)  
But you first write (git remote -v) then write (git branch) just to make sure you write right

---

# So what we had learn ?

1. create your files
2. git add your files
3. git commit -m "we fixed the bug"
4. git push origin main

# some other commands like:

- git status => every time to see what's up
- git reset head fileName => this to unAdd the fileName you just added, you will remove it from the addition
- git remote -v => this gives you origin and link
- git branch => this to make you branch like main
