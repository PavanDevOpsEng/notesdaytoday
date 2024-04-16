IMP Notes:

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

# To pull the changes to EC2 intance 

1 Clone the git hub in ec2 

$ git clone https://github.com/PavanDevOpsEng/ShellScripts.git

2. To pull the cahnges in time use pull command

$ git pull 
