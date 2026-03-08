# Git Industry Commands

## 1. Git Configuration Commands

---
### Command Name -git config --global user.name
### Syntax
git config --global user.name "Your Name"
### Purpose
Sets the Git username globally for all repositories.
### Example
git config --global user.name "Siva"
### Screenshot Proof
(Add screenshot here)

---

### Command Name - git config --global user.email
### Syntax
git config --global user.email "your@email.com"
### Purpose
Sets Git email globally for commits.
### Example
git config --global user.email "siva@gmail.com"
### Screenshot Proof
(Add screenshot here)

---

### Command Name-git config --list
### Syntax
git config --list
### Purpose
Displays all Git configuration settings.
### Example
git config --list
### Screenshot Proof
(Add screenshot here)

---
### Command Name -git config --unset user.name
### Syntax
git config --unset user.name
### Purpose
Removes a configuration value.
### Example
git config --unset user.name
### Screenshot Proof
(Add screenshot here)


## 2. Repository Setup Commands
### Command Name
git init
### Syntax
git init
### Purpose
Initializes a new Git repository.
### Example
git init
### Screenshot Proof
(Add screenshot here)

### Command Name
git clone
### Syntax
git clone <repository-url>
### Purpose
Copies a GitHub repository to your local machine.
### Example
git clone https://github.com/user/repo.git
### Screenshot Proof
(Add screenshot here)

---

### Command Name
git clone --branch
### Syntax
git clone --branch <branch-name> <repo-url>
### Purpose
Clones a specific branch of a repository.
### Example
git clone --branch main https://github.com/user/repo.git
### Screenshot Proof
(Add screenshot here)

---

### Command Name
git clone --depth
### Syntax
git clone --depth <number> <repo-url>
### Purpose
Clones repository with limited commit history.
### Example
git clone --depth 1 https://github.com/user/repo.git
### Screenshot Proof
(Add screenshot here)


## 3. Repository Status & Inspection
---

### Command Name - git status
### Syntax
git status
### Purpose
Shows current repository status.
### Example
git status
### Screenshot Proof
(Add screenshot here)

---

### Command Name
git log
### Syntax
git log
### Purpose
Shows commit history.
### Example
git log
### Screenshot Proof
(Add screenshot here)

---

### Command Name - git log --oneline
### Syntax
git log --oneline
### Purpose
Shows commit history in short form.
### Example
git log --oneline
### Screenshot Proof
(Add screenshot here)

---

### Command Name  - git log --graph
### Syntax
git log --graph
### Purpose
Shows commit history in graph format.
### Example
git log --graph
### Screenshot Proof
(Add screenshot here)

---

### Command Name - git show
### Syntax
git show
### Purpose
Displays details of a commit.
### Example
git show
### Screenshot Proof
(Add screenshot here)

---

### Command Name -git diff

### Syntax
git diff
### Purpose
Shows difference between file changes.
### Example
git diff
### Screenshot Proof
(Add screenshot here) 



### Command Name: git diff --staged

Syntax:
git diff --staged

Purpose:
This command shows the changes that are added to the staging area but not yet committed.

Example:
git add git_industry_commands.md
git diff --staged


### Command Name: git blame

Syntax:
git blame <file-name>

Purpose:
The git blame command shows which user last modified each line of a file along with the commit ID and date. It helps identify who made changes to specific lines.

Example:
git blame git_industry_commands.md



### Command Name: git reflog

Syntax:
git reflog

Purpose:
The git reflog command displays the history of updates to the HEAD pointer in a repository. It records actions such as commits, merges, checkouts, and resets. It is useful for recovering lost commits.

Example:
git reflog

### Command Name: git shortlog

Syntax:
git shortlog
Purpose:
The git shortlog command provides a summarized log of commits grouped by author. It shows how many commits each contributor made.
Example:
git shortlog

### 4 . FILE TRACKING COMMANDS 
### Command Name: git add
Syntax:
git add <file-name>
Purpose:
Adds a specific file to the staging area.
Example:
git add git_industry_commands.md


### Command Name: git add .
Syntax:
git add .
Purpose:
Adds all modified files to the staging area.
Example:
git add .

### Command Name: git add -p
Syntax:
git add -p
Purpose:
Adds changes to staging area step by step.
Example:
git add -p

### Command Name: git restore
Syntax:
git restore <file-name>
Purpose:
Restores the file to the last committed version.
Example:
git restore git_industry_commands.md

### Command Name: git restore --staged
Syntax:
git restore --staged <file-name>
Purpose:
Removes the file from the staging area.
Example:
git restore --staged git_industry_commands.md

### Command Name: git rm
Syntax:
git rm <file-name>
Purpose:
Deletes a file from the repository.
Example:
git rm sample.txt


### Command Name: git mv
Syntax:
git mv <old-name> <new-name>
Purpose:
Renames or moves a file.
Example:
git mv old.txt new.txt

### 5. COMMIT COMMANDS
### Command Name: git commit
Syntax:
git commit
Purpose:
Creates a commit and opens editor to write message.
Example:
git commit

### Command Name: git commit -m
Syntax:
git commit -m "message"
Purpose:
Creates a commit with a message.
Example:
git commit -m "Added new changes"

### Command Name: git commit --amend
Syntax:
git commit --amend
Purpose:
Modifies the last commit.
Example:
git commit --amend

### Command Name: git commit --no-edit
Syntax:
git commit --amend --no-edit
Purpose:
Amends last commit without changing message.
Example:
git commit --amend --no-edit

### 6. BRANCH MANAGEMENT COMMANDS 
### Command Name: git branch
Syntax:
git branch
Purpose:
Shows all local branches.
Example:
git branch

### Command Name: git branch -a
Syntax:
git branch -a
Purpose:
Shows all local and remote branches.
Example:
git branch -a

### command name : git branch -d
Syntax:
git branch -d <branch-name>
Purpose:
Deletes a branch safely.
Example:
git branch -d feature1


#### Command Name: git branch -D
Syntax:
git branch -D <branch-name>
Purpose:
Force deletes a branch.
Example:
git branch -D feature1

### Command Name: git checkout
Syntax:
git checkout <branch-name>
Purpose:
Switches to another branch.
Example:
git checkout master

### Command Name: git checkout -b
Syntax:
git checkout -b <branch-name>
Purpose:
Creates and switches to a new branch.
Example:
git checkout -b feature1

### Command Name: git switch
Syntax:
git switch <branch-name>
Purpose:
Switches to another branch.
Example:
git switch master

### Command Name: git switch -c
Syntax:
git switch -c <branch-name>
Purpose:
Creates and switches to a new branch.
Example:
git switch -c new-feature


###  MERGE & INTEGRATION COMMANDS 
### Command Name: git merge
Syntax:
git merge <branch-name>
Purpose:
Combines changes from another branch.
Example:
git merge feature1

### Command Name: git merge --no-ff
Syntax:
git merge --no-ff <branch-name>
Purpose:
Merges a branch and keeps a merge commit.
Example:
git merge --no-ff feature1

### 8. remote repository commands
### Command Name: git remote
Syntax:
git remote
Purpose:
Shows remote repository names.
Example:
git remote

### Command Name: git remote -v
Syntax:
git remote -v
Purpose:
Shows remote repository URLs.
Example:
git remote -v

### Command Name: git remote add
Syntax:
git remote add <name> <url>
Purpose:
Adds a new remote repository.
Example:
git remote add origin https://github.com/user/repo.git

### Command Name: git remote remove
Syntax:
git remote remove <name>
Purpose:
Removes a remote repository.
Example:
git remote remove origin

### Command Name: git fetch
Syntax:
git fetch
Purpose:
Downloads changes from remote repository.
Example:
git fetch

### Command Name: git fetch --all
Syntax:
git fetch --all
Purpose:
Fetches changes from all remote repositories.
Example:
git fetch --all

### Command Name: git pull
Syntax:
git pull
Purpose:
Fetches and merges changes from remote repository.
Example:
git pull

### Command Name: git pull --rebase
Syntax:
git pull --rebase
Purpose:
Fetches changes and applies them using rebase.
Example:
git pull --rebase


### Command Name: git push
Syntax:
git push
Purpose:
Uploads commits to remote repository.
Example:
git push


### Command Name: git push -u origin branch-name
Syntax:
git push -u origin <branch-name>
Purpose:
Pushes branch and sets upstream branch.
Example:
git push -u origin master

### Command Name: git push --force
Syntax:
git push --force
Purpose:
Force pushes changes to remote repository.
Example:
git push --force

### 9 . stash commands
### Command Name: git stash
Syntax:
git stash
Purpose:
Temporarily saves uncommitted changes.
Example:
git stash

### Command Name: git stash list
Syntax:
git stash list
Purpose:
Shows list of saved stashes.
Example:
git stash list

### Command Name: git stash pop
Syntax:
git stash pop
Purpose:
Applies latest stash and removes it.
Example:
git stash pop

### Command Name: git stash apply
Syntax:
git stash apply
Purpose:
Applies stash without removing it.
Example:
git stash apply


### Command Name: git stash drop
Syntax:
git stash drop
Purpose:
Deletes a specific stash.
Example:
git stash drop stash@{0}

### COMMAND NAME : git statsh clear
Syntax:
git stash clear
Purpose:
Deletes all stashes.
Example:
git stash clear

### 10 . RESET &UNDO COMMMANDS
### Command Name: git reset
Syntax:
git reset <commit-id>
Purpose:
Moves HEAD to a previous commit.
Example:
git reset 3f2a1c

### Command Name: git reset --soft
Syntax:
git reset --soft <commit-id>
Purpose:
Resets commit but keeps changes staged.
Example:
git reset --soft HEAD~1


### Command Name: git reset --mixed
Syntax:
git reset --mixed <commit-id>
Purpose:
Resets commit and unstages changes.
Example:
git reset --mixed HEAD~1

### Command Name: git reset --hard
Syntax:
git reset --hard <commit-id>
Purpose:
Resets commit and deletes all changes.
Example:
git reset --hard HEAD~1


### Command Name: git revert
Syntax:
git revert <commit-id>
Purpose:
Creates a new commit to undo changes.
Example:
git revert 3f2a1c

### Command Name: git clean -f
Syntax:
git clean -f
Purpose:
Removes untracked files.
Example:
git clean -f

### Command Name: git clean -fd
Syntax:
git clean -fd
Purpose:
Removes untracked files and directories.
Example:
git clean -fd

### 11.REBASING COMMANDS
### Command Name: git rebase
Syntax:
git rebase <branch-name>
Purpose:
Applies commits from one branch onto another branch.
Example:
git rebase master

### Command Name: git rebase -i
Syntax:
git rebase -i <commit-id>
Purpose:
Performs interactive rebase to edit commits.
Example:
git rebase -i HEAD~3

### Command Name: git rebase --continue
Syntax:
git rebase --continue
Purpose:
Continues rebase after resolving conflicts.
Example:
git rebase --continue

### Command Name: git rebase --abort
Syntax:
git rebase --abort
Purpose:
Cancels the rebase process.
Example:
git rebase --abort


### 12.cherry pick& patch commands 
### Command Name: git cherry-pick
Syntax:
git cherry-pick <commit-id>
Purpose:
Applies a specific commit from another branch.
Example:
git cherry-pick a1b2c3

### Command Name: git format-patch
Syntax:
git format-patch <commit-id>
Purpose:
Creates patch files from commits.
Example:
git format-patch HEAD~1

### Command Name: git apply
Syntax:
git apply <patch-file>
Purpose:
Applies changes from a patch file.
Example:
git apply patch-file.patch

### Command Name: git am
Syntax:
git am <patch-file>
Purpose:
Applies patch and creates commit.
Example:
git am patch-file.patch

### 13.Tagging commands 
### Command Name: git tag
Syntax:
git tag
Purpose:
Lists all tags in repository.
Example:
git tag

### Command Name: git tag -a
Syntax:
git tag -a <tag-name> -m "message"
Purpose:
Creates an annotated tag.
Example:
git tag -a v1.0 -m "First version"

### Command Name: git tag -d
Syntax:
git tag -d <tag-name>
Purpose:
Deletes a tag.
Example:
git tag -d v1.0

### Command Name: git push origin --tags
Syntax:
git push origin --tags
Purpose:
Pushes all tags to remote repository.
Example:
git push origin --tags

### 14 . Submodule commands 
### Command Name: git submodule add
Syntax:
git submodule add <repository-url>
Purpose:
Adds another repository as a submodule.
Example:
git submodule add https://github.com/user/project.git

### Command Name: git submodule init
Syntax:
git submodule init
Purpose:
Initializes submodules in the repository.
Example:
git submodule init

### Command Name: git submodule update
Syntax:
git submodule update
Purpose:
Updates submodules to the correct version.
Example:
git submodule update

### 15. Debbugging commands 
### Command Name: git bisect
Syntax:
git bisect
Purpose:
Helps find the commit that introduced a bug.
Example:
git bisect

### Command Name: git bisect start
Syntax:
git bisect start
Purpose:
Starts the bisect process.
Example:
git bisect start

### Command Name: git bisect good
Syntax:
git bisect good <commit-id>
Purpose:
Marks a commit as good (no bug).
Example:
git bisect good a1b2c3

### Command Name: git bisect bad
Syntax:
git bisect bad <commit-id>
Purpose:
Marks a commit as bad (has bug).
Example:
git bisect bad d4e5f6
 
 ### ! Github Features to Demonstrate
 ### Command Name: Create GitHub Repository
Syntax:
Create repository from GitHub website.
Purpose:
Creates a new repository to store project code.
Example:
1. Go to GitHub
2. Click New Repository
3. Enter repository name
4. Click Create Repository 

### Command Name: Add README
Syntax:
Create README.md file
Purpose:
Adds project description to the repository.
Example:
Create README.md in repository

### Command Name: Add .gitignore
Syntax:
Create .gitignore file
Purpose:
Ignores unnecessary files from Git tracking.
Example:
Create .gitignore and add node_modules/

### Command Name: Create Issue
Syntax:
Create issue from GitHub Issues tab
Purpose:
Used to report bugs or tasks.
Example:
Go to Issues → Click New Issue

### Command Name: Assign Issue
Syntax:
Assign issue to collaborator
Purpose:
Assigns responsibility for fixing the issue.
Example:
Open issue → Assign to user

### Command Name: Create Branch
Syntax:
git branch <branch-name>
Purpose:
Creates a new branch.
Example:
git branch feature1

### Command Name: Push Branch
Syntax:
git push -u origin <branch-name>
Purpose:
Pushes branch to remote repository.
Example:
git push -u origin feature1

### Command Name: Create Pull Request
Syntax:
Create PR from GitHub Pull Requests tab
Purpose:
Requests merging branch changes into main branch.
Example:
Go to Pull Requests → New Pull Request

### Command Name: Review Pull Request
Syntax:
Review PR from GitHub
Purpose:
Checks code before merging.
Example:
Open Pull Request → Add review

### Command Name: Merge Pull Request
Syntax:
Merge PR in GitHub
Purpose:
Combines branch changes into main branch.
Example:
Click Merge Pull Request

### Command Name: Resolve Merge Conflict
Syntax:
Edit conflicting files and commit
Purpose:
Fixes conflicts between branches.
Example:
Fix code → git add . → git commit

### Command Name: Close Issue
Syntax:
Close issue in GitHub
Purpose:
Marks issue as completed.
Example:
Click Close Issue

### Command Name: Add Labels
Syntax:
Add labels from GitHub
Purpose:
Categorizes issues and pull requests.
Example:
Add label "bug"

### Command Name: Add Collaborators
Syntax:
Add users in repository settings
Purpose:
Allows others to contribute to repository.
Example:
Settings → Collaborators → Add user

### Command Name: Commit and Push File
Syntax:
git add git_industry_commands.md
git commit -m "Added industry level Git commands practice"
git push
Purpose:
Adds file to repository and pushes to GitHub.
Example:
git add git_industry_commands.md
git commit -m "Added industry level Git commands practice"
git push

### Command Name: Submission
Syntax:
Submit repository link
Purpose:
Share GitHub repository for evaluation.
Example:
Submit GitHub repository link containing git_industry_commands.md