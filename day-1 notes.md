###### **Git**

A version control tool

Works locally on your computer

Tracks code changes (commit, branch, merge)



###### **GitHub**

A cloud platform for Git repositories

Works online

Used to store, share, and collaborate on code



###### Pushing files from Git to Github 

-------------------------------------------

C:\\Users\\girim\\OneDrive\\Desktop\\training(3-2)>git init   <--------

Initialized empty Git repository in C:/Users/girim/OneDrive/Desktop/training(3-2)/.git/



C:\\Users\\girim\\OneDrive\\Desktop\\training(3-2)>git add .  <--------



C:\\Users\\girim\\OneDrive\\Desktop\\training(3-2)>git commit -m "my first commit"   <------

Author identity unknown



\*\*\* Please tell me who you are.



Run



&nbsp; git config --global user.email "you@example.com"

&nbsp; git config --global user.name "Your Name"



to set your account's default identity.

Omit --global to set the identity only in this repository.



fatal: unable to auto-detect email address (got 'girim@LAPTOP-U7Q6E0LM.(none)')



C:\\Users\\girim\\OneDrive\\Desktop\\training(3-2)>git config --global user.email "pranaykumar1005@gmail.com"   <-------



C:\\Users\\girim\\OneDrive\\Desktop\\training(3-2)>git config --global user.name "Pranaykumar436"    <------



C:\\Users\\girim\\OneDrive\\Desktop\\training(3-2)>git commit -m "my first commit"     <------

\[master (root-commit) 1d26a27] my first commit

&nbsp;2 files changed, 194 insertions(+)

&nbsp;create mode 100644 index.html

&nbsp;create mode 100644 style.css



C:\\Users\\girim\\OneDrive\\Desktop\\training(3-2)>git remote add origin https://github.com/Pranaykumar436/Training-day-1.git   <----



C:\\Users\\girim\\OneDrive\\Desktop\\training(3-2)>git branch   <-----

\* master



C:\\Users\\girim\\OneDrive\\Desktop\\training(3-2)>git branch -M master    <-----



C:\\Users\\girim\\OneDrive\\Desktop\\training(3-2)>git push -u origin master   <-----

info: please complete authentication in your browser...

Enumerating objects: 4, done.

Counting objects: 100% (4/4), done.

Delta compression using up to 12 threads

Compressing objects: 100% (4/4), done.

Writing objects: 100% (4/4), 1.58 KiB | 1.58 MiB/s, done.

Total 4 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)

To https://github.com/Pranaykumar436/Training-day-1.git

&nbsp;\* \[new branch]      master -> master

branch 'master' set up to track 'origin/master'.

