## ** 1 ==> create a repo on github **

### How Git actually works:
```
working directory ==> staging area ==> localRepo ==> remoteRepo
```

Some git commands:
```
git add <filename >             ==> from WD to staging area
git rm --cached <filename>      ==> from staging area to WD

git commit -m "message"         ==> from staging area to localRepo
git commit -am "message"        ==> from WD to localRepo

git branch                      ==> see all branches
git branch master               ==> create a new branch called master
git switch master               ==> switch to master branch
git merge main                  ==> merge main branch to master branch
git branch -d main              ==> delete main branch

git log                         ==> see logs of files
git log --oneline
git log --oneline --graph --decorate --all

git remote -v                   ==> get remote remoteRepo
 
git push <remoteName> <branchName>      ==> from localRepo to remoteRepo
git push -u origin master

git pull <remoteName>                   ==> from remoteRepoRepo to localRepo
git pull origin


git config -l                   ==> list of configration
git help config
git config -l --show-origin
git config --global --edit      ==> open config file by editor

git config --global user.name                   ==> get user name 
git config --global user.name "Mohamed Badr"    ==> set user name
git config --global --unset user.name           ==> unset user name

git config --global user.email
git config --global user.email "mohamed@gmail.com"



```


### Add a new developer to work on your repo
```
github
remoteRepo
settings
collaborators

```



