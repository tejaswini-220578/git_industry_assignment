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

-- ### Command Name
git config --unset user.name
### Syntax
git config --unset user.name
### Purpose
Removes a configuration value.
### Example
git config --unset user.name
### Screenshot Proof
(Add screenshot here)

--

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

### Command Name
git status
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