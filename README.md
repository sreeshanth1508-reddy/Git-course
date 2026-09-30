# Git Course – Personal Study Notes

This repository contains my personal notes taken while studying **Git and GitHub**. The notes cover core concepts, commands, and workflows, written as I followed along during the course.

---

## 📄 Files

### [`gitcourse.txt`](./gitcourse.txt)
The main notes file. Topics covered include:

- **Setting up a Git repository** – `git init`, the `.git` directory
- **Project directory structure** – working directory, staging area, and commit history
- **Staging and committing** – `git add`, `git commit`, skipping the staging area with `git commit -a`
- **Checking status and history** – `git status`, `git log`, `git log --pretty=oneline`
- **Removing files from Git** – `git rm --cached`
- **Connecting to GitHub** – generating SSH keys, adding a remote with `git remote add origin`, pushing with `git push`
- **Remote repository info** – `git remote -v` (fetch and push URLs)
- **Tags** – lightweight tags (`git tag v1.0`) and annotated tags (`git tag -a v1.0 -m "message"`), viewing tags with `git show`
- **Branches** – creating (`git switch -c` / `git checkout -b`), listing (`git branch`, `git branch --all`), switching (`git switch`), and deleting (`git branch -d`) branches
- **Merging** – pulling before merging (`git pull origin main`), merging a branch (`git merge feature1`), pushing the result back to remote

### [`newfileinfeature1.txt`](./newfileinfeature1.txt)
A small note created inside the `feature1` branch to observe branch behaviour — specifically how a file created in one branch is not visible in another branch until it is merged.

---

## 🗂️ Branch Structure

| Branch | Purpose |
|--------|---------|
| `main` | Primary branch with all finalized notes |
| `feature1` | Branch used to practise creating and merging branches |

---

## 🏷️ Tags

| Tag | Description |
|-----|-------------|
| `v1.0` | Marked during the tags section of the course |
| `v1.1` | Second tag added while studying annotated vs lightweight tags |

---

*These notes are for personal learning and reference.*
