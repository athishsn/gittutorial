# 🌟 GitHub Tutorial for Beginners

Welcome to the **GitHub Tutorial Repository**! This guide is designed for beginners to learn the basics of Git and GitHub. By following this step-by-step tutorial, you'll understand how to create repositories, commit changes, work with branches, and collaborate effectively. 🚀

---

## 🛠️ Prerequisites

Before starting, make sure you have the following:
- **Git Installed**: [Download Git](https://git-scm.com/downloads)
- A **GitHub Account**: [Sign up here](https://github.com/)

---

## 📦 Getting Started

1. Clone this repository to your local machine using the command `git clone https://github.com/your-username/github-tutorial.git`, and navigate into the folder with `cd github-tutorial`.

2. If you’re starting a new project from scratch, you can initialize a Git repository using `git init`.

3. To check the status of your working directory at any point, use `git status`.

4. To stage changes, use `git add <filename>` for a specific file or `git add .` to stage all changes.

5. Once staged, save your changes with a meaningful commit message using `git commit -m "Your commit message"`.

---

## 🌿 Working with Branches

1. To create a new branch, use `git branch <branch-name>`. 

2. Switch to the new branch with `git checkout <branch-name>`.

3. For convenience, you can create and switch to a branch in one step using `git checkout -b <branch-name>`.

4. To merge a branch back into your main branch, switch to the target branch (e.g., `main`) using `git checkout main` and then merge the other branch with `git merge <branch-name>`.

5. After merging, you can delete the branch with `git branch -d <branch-name>`.

---

## 🔗 Pushing and Pulling Changes

1. If you haven’t already connected your local repository to a remote repository, add a remote URL with `git remote add origin https://github.com/your-username/github-tutorial.git`.

2. Push changes from your local branch to the remote repository using `git push -u origin <branch-name>`.

3. To fetch changes from the remote repository without merging them, use `git fetch`.

4. To fetch and merge changes from the remote branch into your local branch, use `git pull`.

---

## 🧹 Additional Commands

1. To view the commit history, use `git log`.

2. To see unstaged changes, use `git diff`.

3. If you want to undo staging, you can use `git reset <filename>`.

---

## 📚 Resources

- [GitHub Docs](https://docs.github.com)
- [Git Cheat Sheet](https://education.github.com/git-cheat-sheet-education.pdf)
- [Pro Git Book](https://git-scm.com/book/en/v2)

---

## 🎉 Congratulations!

You've completed the GitHub tutorial for beginners! Practice these commands, and you'll become a pro in no time. Feel free to experiment with this repository or create your own. Happy coding! 🚀
