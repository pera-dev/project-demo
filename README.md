# Demo Project

This is Demo Project for understanding basic github for teams

## Github Pages

[Preview](https://peracs.github.io/project-demo/) this web page in browser

# Some useful Git commands

Start a Local git repository/repo
```bash
git init
```
Clone a remote repo [ Download ]
```bash
git clone https://github.com/PeraCS/project-demo
```
Create branch
```bash
git checkout -b branch-name
```
Switch to a branch
```bash
git checkout branch
```
* Note without -b it will switch to a existing branch

Delete a branch
```bash
git branch -d branch-name
```
# Useful commands ro sync with remote repo

Updates current working branch with latest commits from remote repo
```bash
git pull
```
* Uses this everytime you started working

Uploads your local branch commits to remote 

```bash
git push
```
* Before you do that you need add your remote repo using following command
  
  ```bash
  git add origin https://github.com/PeraCS/project-demo
  ```
