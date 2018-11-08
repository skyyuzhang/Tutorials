# create a new reository on the command line 
## move to the repository you want it to push
```bash
git init
git add -A
git commit -m "whatever you want to write"
git remote add origin https://github/user_name/project.git
git push -u origin master
```
NOTE: user_name 
# add submodule
```bash
git submodule add <rpository> <path>
git status
git add .gitmodules <repository path>
git commit -m "add libcanard"
git submodule init
git push -u origin master
```
## demo
```bash
git submodule add https://github.com/UAVCAN/libcanar.git
git add .gitmodules libcanard
```
