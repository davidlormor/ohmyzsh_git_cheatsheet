oh my zsh git shortcuts
=======================
**g** `$ git`
*Displays basic info about git.*

Status and Logs
---------------
**gst** `$ git status`
*Show the status of the working tree.*
**gd** `$ git diff`
*Show changes between commits, commit and working tree, etc.*
**gdc** `$ git diff --cached`
*View changes staged for next commit*
**gcount** `$ git shortlog -sn`

**glg** `$ git log --stat --max-count=10`
**glgg** `$ git log --graph --max-count=10`
**glgga** `$ git log --graph --decorate --all`
**glo** `$ git log --oneline --decorate --color`
**glog** `$ git log --oneline --decorate --color --graph`
**gwc** `$ git whatchanged -p --abbrev-commit --pretty=medium`

Interacting with Remotes
------------------------
**gl** `$ git pull`
**gup** `$ git pull --rebase`
**gp** `$ git push`
**gr** `$ git remote`
**grv** `$ git remote -v`
**grmv** `$ git remote rename`
**grrm** `$ git remote remove`
**grset** `$ git remote set-url`
**grup** `$ git remote update`
**gpoat** `$ git push origin --all && git push origin --tags`

Committing Changes
------------------
**gc** `$ git commit -v`
**gc!** `$ git commit -v --amend`
**gca** `$ git commit -v -a`
**gca!** `$ git commit -v -a --amend`
**gcmsg** `$ git commit -m`
**ga**`$ git add`

Branching
---------
**gco** `$ git checkout`
**gcm** `$ git checkout master`
**gb** `$ git branch`
**gba** `$ git branch -a`

Merging and Rebasing
--------------------
**gm** `$ git merge`
**grbi** `$ git rebase -i`
**grbc** `$ git rebase --continue`
**grba** `$ git rebase --abort`

Stashing
--------
**gsts** `$ git stash show --text`
**gsta** `$ git stash`
**gstp** `$ git stash pop`
**gstd** `$ git stash drop`

Undoing changes
---------------
**grh** `$ git reset HEAD`
**grhh** `$ git reset HEAD --hard`
**gclean** `$ git reset --hard && git clean -dfx`

Cherry picking
--------------
**gcp** `$ git cherry-pick`