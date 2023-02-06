# how to use git and github

## what you must have

![Alt text]( https://github.com/01134K/How-to-use-git-and-GitHub/blob/master/pic/git-github.png?raw=true )
> git link download : https://git-scm.com/download/win

> GitHub link : https://github.com/


## login github on terminal

```
git config --global user.email "you@example.com"
git config --global user.name "Your Name"
```

## First setup github project


> Create new repository

![Alt text]( https://github.com/01134K/How-to-use-git-and-GitHub/blob/master/pic/new2.png?raw=true )

> set project name

![Alt text]( https://github.com/01134K/How-to-use-git-and-GitHub/blob/master/pic/reponame.png?raw=true )

> Create repository

![Alt text](https://github.com/01134K/How-to-use-git-and-GitHub/blob/master/pic/crepo.png?raw=true)



```

git init

git add .

git commit -am "<commit name>"

git remote add origin <url github>

git push -u origin <name branch>

```
## new branch
```
git branch <branch name>

git checkout <branch name>

git add .

git commit -m "<name>"

git push -u origin <name branch>
```

## pull 
```
 git pull <remote> <branch>
```
