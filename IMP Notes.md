IMP Notes:



## Git 

steps:

Create repo in Github
Clone repo in local laptop
Start developing
Add the files to temp area
  $ git add <file-name>
Commit the changes
  $ git commit -m "why-you-commited"
Push the changes to GitHub/Central repo
  $ git push -u origin main

naming convention: use small case with Hyphons(-). No spaces

# Over all :

git add . ; git commit -m "some-message"; git push -u origin main


Example : 

Pavans-MacBook-Air:notesdaytoday pavanittamalla$ git commit -m "first commit"
On branch master
Your branch is based on 'origin/master', but the upstream is gone.
  (use "git branch --unset-upstream" to fixup)

Untracked files:
	IMP Notes.md

nothing added to commit but untracked files present
Pavans-MacBook-Air:notesdaytoday pavanittamalla$ 
Pavans-MacBook-Air:notesdaytoday pavanittamalla$ git add
Nothing specified, nothing added.
Maybe you wanted to say 'git add .'?
Pavans-MacBook-Air:notesdaytoday pavanittamalla$ .
-bash: .: filename argument required
.: usage: . filename [arguments]
Pavans-MacBook-Air:notesdaytoday pavanittamalla$ git add .
Pavans-MacBook-Air:notesdaytoday pavanittamalla$ 
Pavans-MacBook-Air:notesdaytoday pavanittamalla$ 
Pavans-MacBook-Air:notesdaytoday pavanittamalla$ git commit -m "first commit"
[master 2d2a474] first commit
 1 file changed, 48 insertions(+)
 create mode 100644 IMP Notes.md
Pavans-MacBook-Air:notesdaytoday pavanittamalla$ 
Pavans-MacBook-Air:notesdaytoday pavanittamalla$ git branch -M main
Pavans-MacBook-Air:notesdaytoday pavanittamalla$ 
Pavans-MacBook-Air:notesdaytoday pavanittamalla$ git push -u origin main
Counting objects: 5, done.
Delta compression using up to 8 threads.
Compressing objects: 100% (4/4), done.
Writing objects: 100% (5/5), 953 bytes | 953.00 KiB/s, done.
Total 5 (delta 0), reused 0 (delta 0)
To https://github.com/PavanDevOpsEng/notesdaytoday.git
 * [new branch]      main -> main
Branch 'main' set up to track remote branch 'main' from 'origin'.
Pavans-MacBook-Air:notesdaytoday pavanittamalla$ 
Pavans-MacBook-Air:notesdaytoday pavanittamalla$ 
Pavans-MacBook-Air:notesdaytoday pavanittamalla$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean
Pavans-MacBook-Air:notesdaytoday pavanittamalla$ 



# To pull the changes to EC2 intance 

1 Clone the git hub in ec2 

$ git clone https://github.com/PavanDevOpsEng/ShellScripts.git

2. To pull the cahnges in time use pull command

$ git pull 


### 

Adding an Ec2 Intance in AWS ( Class 6 )

- Create an EC2 instance by selecting the AMI ( devops-practice)
username and password based
---------------------------
RHEL9 -> Latest redhat enterprise OS
CentOS 9
RHEL9 == CentOS9

ec2-user
DevOps321
AMI --> devops-practice --> us-east-1 region

$ ssh ssh ec2-user@54.211.223.218
$ password : DevOps321

## Now we can work on the shell scripts