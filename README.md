### git and github tutorials
### init means im initializing a new repository ie git init
### readme turns green after initialization git repository
### initially U symbol infront of readme file meaning untracked
### after git add readme it changes to A meaning added 
### then with changes inside the readme it changes to M meaning modified
### i can check the staus of readme so i use 'git status'
### to remove or unstage readme file use'git rm --chached README.md'
### since the readme file is modified it has be added to git again
### so the command git add readme.md and A is appeared infront of the readme file
### i can check whether a file is present in git or not by using the command git status
### first we need to config by adding user name and user email
### so git config git config --global user.name "name"
### now email git config --global user.email "dayashankarnp1998@gmail.com"
### git commit -m "----commit-----"
### change my git branch from master to main by using git branch -M main
### add local repository to main repo git remote add origin https://github.com/Dayashankarnp/gitrepository.git
### to check whether git repo is add use git remote -v
### now i need to push the my origin to main git push origin main
### if i added new file app.py and i need to push it to repo follow same steps first git add . and then git commit and then git push origin main
### if i have created new file in main repo i need to to pull it to local repo so i use git pull origin main
### some changes
### git ignore is used to ignore certain high memory files from pushing it to main repo 
### create .gitignore file in git and choose template to be python and commit changes and to get that to local repo git pull origin main
### consider i created my environment with name myenv so it has given python packages and i dont have no need
 ### to send it to main so inside the .gitignore file i will add myenv/ along with already written venv/ and all other ignorable files
### and when i use the git add . command myenv will not be added
### how to clone a repo
### first create a clone folder and change the currrent directory to that folder cd C:\GIT\clonerepo
### my repository has a http link in code section copy and paste it after git clone http:link
 ### lets say that i made some changes in the readme file using github website and i also made changes in my local repo
### if i'm trying to push changes from local repo to main while the changes from main to local has not been done then it throws a error
### to resolve it first pull the main and then push to main from local repo
### now lets say that many programmers are working on the same project but need to have differnt branches under main branch
### to check the number of branches git branch
### creating new branch git branch developerA
### you can check through git branch
### developerA has the same code as main will be there
### how to switch to branch use git checkout developerA
### now you have made some changes in app.py
### git add . with commit message 
### now merge with main so for that change branch to main git checkout main
### noq merge git merge developerA
