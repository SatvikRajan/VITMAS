# VITMAS
## Basic Commands

### `git init`

Syntax: `git init [repository name]`

initialize an existing directory as a Git repository
   
### `git add` 

Syntax: `git add [file]`

add a file as it looks now to your next commit (stage)

### `git commit` 

Syntax: `git commit -m “[descriptive message]”`

commit your staged content as a new commit snapshot

### `git status` 
  
Syntax: `git status`

show modified files in working directory, staged for your next commit

### `git log` 

Syntax: `git log `

show all commits in the current branch’s history

### `git branch` 

Syntax: `git branch [branch-name]`

create a new branch at the current commit

### `git checkout`   

Syntax: `git checkout [branch-name]`

switch to another branch and check it out into your working directory

### `git merge` 

Syntax: `git merge [branch-name]`

merge the specified branch’s history into the current one

### `git pull` 

Syntax: `git pull <remote> <branch>`

fetch and merge any commits from the tracking remote branch

### `git push`
  
Syntax: `git push [alias] [branch]`

Transmit local branch commits to the remote repository branch

### `git mv`

Syntax: `git mv [existing-path] [new-path]`

change an existing file path and stage the move

### `git clone`
   
Syntax: `git clone [url]`

retrieve an entire repository from a hosted location via URL

### `git remote`
    
Syntax: `git remote add [alias] [url]`
    
add a git URL as an alias

### `git fetch`

Syntax: `git fetch [alias]`
    
fetch down all the branches from that Git remote

### `git diff`
    
Syntax: `git diff`

diff of what is changed but not staged

### `git tag`

Syntax: `git tag/git tag <tag-name>`
    
Lists or creates tags
    
### `git stash`
    
Syntax: `git stash`

Save modified and staged changes

### `git reset`
    
Syntax: `git reset [file]`
    
unstage a file while retaining the changes in working directory

### `git revert`

Syntax: `git revert <commit>`

reverts changes made in a previous commit

### `git rm`
    
Syntax: `git rm [file]`
    
delete the file from project and stage the removal for commit

### `git log`
    
Syntax: `git log branchB..branchA`
    
show the commits on branchA that are not on branchB

### `git log`
    
Syntax: `git log --follow [file]`
    
show the commits that changed file, even across renames
