## Git Cheat Sheet

Brief reference to git commands. Also practice with commit.

* 'git init' - Initialize a local git repo in working directory
* 'git status' - show state of local repo
* 'git log' - last commit history
* 'git log--one line' - compact commit history

### Branching
* 'git branch' - list local branches
* 'git branch newBranch' 'newBranch' - create local branch
* 'git checkout newBranch' - move to 'newBranch'

* 'git add .' - stage current directory in git index
* 'git commit -m "msg"' - commit work to local repo with commit msg
* 'git checkout -b otherBranch' - if it has not yet been created, create this
* 'git pull origin main' - remerge any other branches back into one main branch project

### Remote Repos
* 'git remote add alias url' - add 'alias' as name for remote repo 'url' in project configuration
* 'git push alias aBranch' - push local commits to remote repo 'alias' branch aBranch
* 'git pull alias aBranch' - pull remote aBranch from alias into current local branch
