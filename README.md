Get Basics

- `git init`: create a git repo in current folder.
   - only need to do this once, do not nest repos
- `git status`: tells you the status of the repository
- `git add <FILE>`: adds the <FILE> to the staging area 
- `git commit`: commits the file
- `HEAD`: telling you where you are looking in the history
- `git diff`: show you the diff from all your files to last commit
	- `git diff HEAD <FILE>`
	- `git diff HEAD~2`
	- `git diff <HASH>`
- `git log`
	- `git log --oneline`
- `git checkout <HASH> <FILE>`: reviert file to the version in hash
- `git status`: read that git status tells you to revert a file and/or un-stage a file
- `git checkout <HASH>`: move all the files to their versions in <HASH>
	- `git checkout main`: to back to main branch
	- `git switch main`: might be the same

# Remotes
- `git remote add origin <URL>`: assigns the url, the name "origin" 
- `git push origin main`: pushes the main branch to the origin
- `git pull origin main`: pull the main branch from the remote down to loacl
