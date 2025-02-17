<div align="center">
  <img src="https://git-scm.com/images/logos/downloads/Git-Logo-2Color.png" alt="Git Logo" height="200px"/>
</div>

# 📌 Git Commands Reference  
📁 This repository contains essential Git commands for everyday use. The commands are structured for easy reference.  

---

## 🚀 Initialization
- **Create a new Git repository**:  
  ```bash
  git init
  ```

---

## ⚙️ Configuration
- **Set global username**:  
  ```bash
  git config --global user.name "IndraNaik"
  ```
- **Set global email**:  
  ```bash
  git config --global user.email "pathlavath.indra@gmail.com"
  ```

---

## 📂 File Operations
- **Create a new file**:  
  ```bash
  touch <filename>
  ```
- **Remove a file**:  
  ```bash
  rm <filename>
  ```
- **Restore a deleted file**:  
  ```bash
  git restore <filename>
  ```

---

## 📌 Staging and Commit
- **Check the status of the repository**:  
  ```bash
  git status
  ```
- **Add a file to the staging area**:  
  ```bash
  git add <filename>
  ```
  ```bash
  git add .
  ```
- **Commit changes with a message**:  
  ```bash
  git commit -m "your commit message"
  ```

---

## 🌿 Branching
- **Create a new branch**:  
  ```bash
  git checkout -b <branch_name>
  ```
- **Switch between branches**:  
  ```bash
  git checkout <branch_name>
  ```
  ```bash
  git switch <branch_name>
  ```
- **List all branches**:  
  ```bash
  git branch
  ```
  ```bash
  git branch -a
  ```
  ```bash
  git branch -r
  ```

---

## 📜 Logs
- **View commit history**:  
  ```bash
  git log
  ```
- **View concise commit history**:  
  ```bash
  git log --oneline
  ```

---

## ❌ Remove from Staging
- **Unstage a file (remove from index but keep in working directory)**:  
  ```bash
  git rm --cached <filename>
  ```

---

## 🛠️ Miscellaneous
- **View all files, including hidden ones**:  
  ```bash
  ls -a
  ```
- **Clear terminal screen**:  
  ```bash
  clear
  ```
- **View command history**:  
  ```bash
  history
  ```

---