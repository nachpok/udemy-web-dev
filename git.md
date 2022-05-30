in the folder that holds the folders we want to maintain in git we initialise the project

```
git init
git status // gives the branch and the list of untracked files
git add PATH //adds the file/folder to the git stand by list
git status // will say wat is ready to be commited and wat is not on the list
git commit -m "Initial commit test run" // commit with message "..."
git log // log of all the commits
```

this part was on local machine, to uplode to github create repository and get clone URL

```
git remote add origin https://github.com/nachpok/test.git
git push -u origin master // add commits to github repository

if dose not work:
git push origin HEAD:main
```

check connection to repository:

```
git remote -v
```

pull from github repository:

```
git clone URL
```
