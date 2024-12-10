# Stages of git
```
1. Modified
2. Staged
3. Commit
```
# Commands
1. git clone {url}

## Give Branch Details
2. git status 

## Commit History
3. git log

## If want to switch back to the previous commit
4.git restore --source {commitHash} --staged --worktree -- .
5.git restore --source {commitHash} --staged --worktree -- <filename>

## To pull changes
6. git pull origin main/master

## Basic Commands
```
git init
git add .
git commit -m "m stands for message"
git remote add origin {url}
```
### -u stands for --set-upstream as we move from local to branch location. This need to use at 1st time after that no need , just use "git push origin main".
git push -u origin main 

### "git remote" gives default name for the remote repository
git remote 

### "git remote -v" -v means verbose that gives link along with branch for eg origin {url}
git remote -v

## To create branch we use branch,checkout and switch commands 
```
1. Switching branches.
2. Restoring files from a specific commit or branch.
3. Checking out a commit into a detached HEAD state.
```
# Create Branch
```
1. git branch branchname --> Creates a branch, does NOT switch	
2. git checkout -b branchname --> Creates a branch and switches to it 
3. git switch -c branchname --> Creates a branch and switches to it
```
# Switch Branch
```
1. git checkout branchname --> only switch branch not create, does not create it if it does not exist.
2. git switch branchname --> switches to a branch
```
# Checkout
```
1. git checkout -b branchname --> Creates a branch and switches to it
2. git checkout branchname --> only switch branch not create, does not create it if it does not exist.
3. git checkout <commitHash> -- <filepath> --> To restore changes of a specific file specific commit.
4. git checkout <commitHash>  -->  To restore changes of specific commit
5. git diff HEAD <commithash> --> To compare changes between current and previous commit
6. git diff HEAD <commithash> -- <filepath> --> This command is used to compare if my app.js is working finr in previous commit.
```
   
