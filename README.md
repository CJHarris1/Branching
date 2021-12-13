## Git Cheat Sheet

### Basic Commands
* 'git init' - Initialize local Git repository
* 'git add .' - Add all files in and under current directory to git index, staging them for the commit
* 'git commit -m "Message"' - commit changes to local repo with commit message "Message"


### Information Commands
* 'git status' - display current status of local working directory/repository
* 'git log or git log --oneline' -shows commits, --oneline in compact form

### Branching Commands
* 'git branch' - List local git branches
* 'git branch newBranch' - creates new branch named newBranch
* 'git checkout newBranch' - check out local branch named 'newBranch'
* 'git branch -M otherBranch' - Rename current branch to 'otherBranch'

### Remote Commands
* 'git remote add origin remoteUrl' - Add alias "origin" for remote repository Url "remoteUrl"
* 'git push origin main' - Push locally-comitted changes to 'main' branch on remote repository
* 'git push -u origin main' - Same, setting "origin main" as default for subsequent 'git push'
