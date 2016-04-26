# Git-Commands
##Create local repository to push from:

<br>echo "# Git-Commands" >> README.md
<br>git init
<br>git add README.md
<br>git commit -m "first commit"
<br>git remote add origin https://github.com/ajantoniou/Git-Commands.git
<br>git push -u origin master

##Push existing repo:
<br>git remote add origin https://github.com/ajantoniou/Git-Commands.git
<br>git push -u origin master
<br>git —version

git config --list

——
##Git Commands:

<br>git init: initialize a git repository in your directory
<br>git status: check the status of the repository
<br>git add file_name: add one file
<br>git add .: add all files
<br>git commit -m “commit message”: commit your files along with a message
<br>git remote add origin: https://github.com/username/reponame.git - the remote url to your GitHub repo
<br>git push origin master: push your files up to github on the master branch
##Git Commands:

<br>git branch: list out branches
<br>git branch branch-name: create a new branch
<br>git checkout branch-name: switch to the newly created branch
<br>git checkout -b branch-name: shortcut! - use this command to create & switch to the new branch
<br>git push origin branch-name: push branch & changes to github
