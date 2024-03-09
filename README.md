### git and github tutorials
init means im initializing a new repository ie git init
readme turns green after initialization git repository
initially U symbol infront of readme file meaning untracked
after git add readme it changes to A meaning added 
then with changes inside the readme it changes to M meaning modified
i can check the staus of readme so i use 'git status'
to remove or unstage readme file use'git rm --chached README.md'
since the readme file is modified it has be added to git again
so the command git add readme.md and A is appeared infront of the readme file
i can check whether a file is present in git or not by using the command git status
first we need to config by adding user name and user email
so git config git config --global user.name "name"
now email git config --global user.email "dayashankarnp1998@gmail.com"
git commit -m "----commit-----"
change my git branch from master to main by using git branch -M main
add local repository to main repo git remote add origin https://github.com/Dayashankarnp/gitrepository.git
to check whether git repo is add use git remote -v
now i need to push the my origin to main git push origin main
