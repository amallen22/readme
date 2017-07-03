#MARKDOWN REFERENCE#

#h1 -> h1
##h2 -> h2
###h3 -> h3
####h4 -> h4
...

//Ejemplo

# My main project
## Description

This *project* is a **demo** of how to ***write*** text with markdown

###Crear enlaces de manera rápida###
Done in [Skylab Coders](http://www.skylabcoders.com/es/)

###Insert images in Markdown adding "!"" before reference word###
![Skylab Coders](http://www.skylabcoders.com/images/403/default.png)

###Crear listados###
- item 1
- item 2
- item 3
    + subitem 1
    + subitem 2
    + subitem 3
        * sub subitem 1
        * sub subitem 3
        * sub subitem 2

###Mark words like tag code###
The function `sum` will return the sum of 2 numbers

###Show code good way###

```
function suma(a,b){
    return a + b
}
sum(3,4)
```


###Commands with terminal###
ls -> list
ls -la -> list with details
cd -> change directory
pwd -> Where i am?
mkdir -> create folder
rm -> remove
rm -rf -> force remove

**Deberes para casa**
Abrir una carpeta con sublime desde terminal

##Start with Git##

Install GitHub in my computer writting **git --version** on the terminal

git add "file_name.html" (add file)
git commit "file_name.html" (commit file)
git st "file_name.html" (file status)

####Config Git [(p10)](https://skylabcoders.github.io/bootcamp-julio2017/?full#10)####

git config --global user.name "John Doe"
git config --global user.email "john@doe.org"
git config --global color.ui auto

Verify config-> git config -l

git init -> create a folder repository
git log -> list commit made before
git log --stat-> more datils about commits
git add -> add file to **staging area**
git commit "file_name.html" -m "file_name.html"

git rm --cached "file_name.html" -> remove for the first time from **staging area**
git reset -> remove from **staging area**


####[Matching local Git with GitHub](https://github.com/amallen22/notes-bootcamp)####

git remote add origin https://github.com/amallen22/notes-bootcamp.git

####How i know if there are a online repository?####
git remote -v

####Push to GitHub repository####
git push -u origin master
-u -> No repeat every time "origin master"
Add user mail and password

####Clone remote repo from GitHub####
git clone -> create a folder with the same name of repo

- Create folder
- Git int
- git remote add

We can start creating a remote repo or local repo, both ways goes to the same place

- Create repo in Github
- git clone "url new repo"

We can *fork* user projects and modify it and made commit, push and every git thinks