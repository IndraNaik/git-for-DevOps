  <div align="center">
  <img src="https://git-scm.com/images/logos/downloads/Git-Logo-2Color.png" alt="GitHub Stats" height="200px"/>
</div>

## This repository contains essential Git commands for everyday use. The commands are organized in a structured manner for easy reference.


# Git Commands

## 1. Initialization
- **Create a new Git repository**:
  
  `git init`

## 2. Configuration
- **Set global username**:
  
  `git config --global user.name "IndraNaik"`

- **Set global email**:
  
  `git config --global user.email "pathlavath.indra@gmail.com"`

## 3. File Operations
- **Create a new file**:
  
  `touch <filename>`

- **Remove a file**:
  
  `rm <filename>`

- **Restore a deleted file**:
  
  `git restore <filename>`

## 4. Staging and Commit
- **Check the status of the repository**:
  
  `git status`

- **Add a file to the staging area**:
  
  `git add <filename>`

  `git add .`

- **Commit changes with a message**:
  
  `git commit -m "your commit message"`

## 5. Branching
- **Create a new branch**:
  
  `git checkout -b <branch_name>`
  

- **Switch between branches**:
  
  `git checkout <branch_name>`

  `git switch <branch_name>`

- **List all branches**:
  
  `git branch`

  `git branch -a`

  `git branch -r`

## 6. Logs
- **View commit history**:
  
  `git log`

- **View concise commit history**:
  
  `git log --oneline`

## 7. Remove from Staging
- **Unstage a file (remove from index but keep in working directory)**:
  
  `git rm --cached <filename>`

## 8. Miscellaneous
- **View all files, including hidden ones**:
  
  `ls -a`

- **Clear terminal screen**:
  
  `clear`

- **View command history**:
  
  `history`