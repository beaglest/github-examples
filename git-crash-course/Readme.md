## Git Hidden Folder
There is a hidden folder called `.git` which tells you that our project is a git repo.

If we want to create a git repo in a new project, we create the folder and initialize that repo `git init`
```
git init
touch Readme.md
# open Readme.md
code Readme.md
# make changes to Readme.md
git commit -a -m "Add readme file"
```
## Cloning

We can clone 3 ways: HTTPS, SSH, and Github CLI

Since we are using GitHub Codespaces we'll create a temporary in our workspace. 

```sh
mkdir /workspace/tmp
cd /workspace/tmp
cd github-examples

```
### HTTPS

```sh
git clone https://github.com/beaglest/github-examples.git

```

## commit

## branches

## remote

## stashing

## merging