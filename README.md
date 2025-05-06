# 🛠️ Git & 🌐 GitHub Guide

## 📌 Overview
- **Git**: A **command-line tool** (Version Control System - VCS) used to track changes in code.
- **GitHub**: A **cloud platform** for **hosting Git repositories** and collaborating with others.

---

## 🧰 Git Setup & Core Commands

### ✅ Install Git
- Download and install Git from: [https://git-scm.com/downloads](https://git-scm.com/downloads)

### 🛠️ Set Global Configurations
```bash
git config --global user.name "<USERNAME>"
git config --global user.email "<EMAIL>"
```

### 🧪 Common Git Commands

| Command | Description |
|--------|-------------|
| `git init .` | 🚀 Initialize a new local Git repository |
| `git status` | 📋 Check the status of your branch and changes |
| `git add .` | ➕ Stage all untracked/modified files for commit |
| `git commit -m "<MESSAGE>"` | 📝 Commit staged changes with a message |
| `git log` | 📜 View the commit history |
| `git push` | ☁️ Push committed changes to a remote (e.g., GitHub) |

---

## ☁️ GitHub Setup & Usage

### 1️⃣ Create GitHub Account
- Sign up at: [https://github.com](https://github.com)

### 2️⃣ Setup SSH (Recommended)
- 🔐 Generate SSH key:  
  👉 [GitHub Docs - Generate SSH](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)

- ➕ Add SSH key to GitHub:  
  👉 [GitHub Docs - Add SSH Key](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account?platform=windows&tool=webui)

### 3️⃣ Create a Repository on GitHub
- Choose **Public** or **Private**
- Copy the **repository URL** (SSH or HTTPS)

### 4️⃣ Push Local Repository to GitHub (First Time Only)
```bash
git remote add origin <CLOUD_REPO_URL>   # 🔗 Link local repo to remote
git branch -M main                       # 🌿 Rename branch to main
git push -u origin main                  # 🚀 Push code to GitHub
```

---

## 🔄 Subsequent Changes (After Initial Push)

Once the repository has been linked and the initial push is done, any future changes can be handled with just the following commands:

```bash
git add .                                # ➕ Stage all changes
git commit -m "<COMMIT_MESSAGE>"         # 📝 Commit with a descriptive message
git push                                 # ☁️ Push to GitHub
```

---

## ✅ Summary

| Git 🛠️ | GitHub 🌐 |
|--------|------------|
| Installed locally | Cloud-based |
| CLI-based commands | Web-based UI & collaboration |
| Tracks versions | Hosts and shares code |
| Works offline | Works online |

