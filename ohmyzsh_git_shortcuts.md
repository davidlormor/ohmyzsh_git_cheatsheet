oh my zsh git shortcuts
=======================
###g 
`$ git`  
*Displays basic info about git.*

Status and Logs
---------------
###gst  
`$ git status`  
*Show the status of the working tree.*
###glg  
`$ git log --stat --max-count=10`  
*Show commit logs for last 10 commits with diffstats.*
###glgg  
`$ git log --graph --max-count=10`  
*Show commit logs for last 10 commits with commit graph.*
###glgga  
`$ git log --graph --decorate --all`  
*Show commit logs for all commits with commit graph.*
###glo  
`$ git log --oneline --decorate --color`  
*Show commit logs with one commit per line.*
###glog  
`$ git log --oneline --decorate --color --graph`  
*Show commit logs with on commit per line on a commit graph.*
###gwc  
`$ git whatchanged -p --abbrev-commit --pretty=medium`  
*Show commit logs with changes for each commit.*
###gd  
`$ git diff`  
*Show changes between commits, commit and working tree, etc.*
###gdc  
`$ git diff --cached`  
*View changes staged for next commit*
###gcount  
`$ git shortlog -sn`  
*Provides a summary of the number of commits by user.*

Interacting with Remotes
------------------------
###gl  
`$ git pull`  
*Fetch from and integrate with another repository or a local branch.*
###gup  
`$ git pull --rebase`  
*Rebase the current branch on top of the upstream branch after fetching.*
###gp  
`$ git push`  
*Update remote refs along with associated objects.*
###gpoat  
`$ git push origin --all && git push origin --tags`  
*Update the origin repository with all commits and tags from the current branch.*
###gr  
`$ git remote`  
*Manage a set of remote repositories.*
###grv  
`$ git remote -v`  
*Show remote url after each remote.*
###grmv  
`$ git remote rename`  
*Rename the specified remote repository.*
###grrm  
`$ git remote remove`  
*Remove the specified remote repository.*
###grset  
`$ git remote set-url`  
*Set the url for a specified remote repository.*
###grup  
`$ git remote update`  
*Fetch updates for a named set of remotes in the repository.*

Committing Changes
------------------
###gc  
`$ git commit -v`  
*Record staged changes to the repository with verbose output at the bottom of the commit message template.*
###gc!  
`$ git commit -v --amend`  
*Overwrite the previous commit with verbose output at the bottom of the commit message template.*
###gca  
`$ git commit -v -a`  
*Stage any modified or deleted files and record changes to the repository with verbose output at the bottom of the commit message template.*
###gca!  
`$ git commit -v -a --amend`  
*Stage any modified or deleted files and overwrite the previous commit with verbose output at the bottom of the commit message template.*
###gcmsg  
`$ git commit -m`  
*Record staged changes to the repository with the given commit message.*
###ga  
`$ git add`  
*Add file contents to the index.*

Branching
---------
###gco  
`$ git checkout`  
*Checkout a branch or paths to the working tree.*
###gcm  
`$ git checkout master`  
*Checkout master branch of current repository.*
###gb  
`$ git branch`  
*List, create, or delete branches.*
###gba  
`$ git branch -a`  
*List both remote-tracking branches and local branches.*

Merging and Rebasing
--------------------
###gm  
`$ git merge`  
*Join two or more development histories together.*
###grbi  
`$ git rebase -i`  
*Choose and edit which commits to rebase onto current branch.*
###grbc  
`$ git rebase --continue`  
*Continue rebase after resolving conflicts.*
###grba  
`$ git rebase --abort`  
*Abort the current rebase operation and reset HEAD to the original branch.*

Stashing
--------
###gsta  
`$ git stash`  
*Stash changes in dirty working directory.*
###gstp  
`$ git stash pop`  
*Remove a stash and apply the changes onto the current working directory.*
###gstd  
`$ git stash drop`  
*Remove a stash.*
###gsts  
`$ git stash show --text`  
*Show the changes recorded in the stash as a diff between the stashed state and its original parent.*

Undoing changes
---------------
###grh  
`$ git reset HEAD`  
*Reset current HEAD to the specified state.*
###grhh  
`$ git reset HEAD --hard`  
*Reset the index and working tree. Any changes to tracked files in the working tree since the given commit are discarded.*
###gclean  
`$ git reset --hard && git clean -dfx`  
*Perform a hard reset and remove all untracked files from the working tree.*

Cherry picking
--------------
###gcp  
`$ git cherry-pick`  
*Cherry pick changes introduced by some existing commits.*