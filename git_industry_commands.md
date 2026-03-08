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