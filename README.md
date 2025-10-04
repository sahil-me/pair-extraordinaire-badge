# 🟢 Pair Extraordinaire Badge Guide ✨

Welcome to the **Pair-Extraordinaire Badge** Guide!

This repo demonstrates how to earn the **Pair-Extraordinaire** achievement badge on GitHub by making **co-authored commits** in pull requests.

![giphy](https://github.com/user-attachments/assets/19a4d159-f9e0-425f-a6f8-5352b66a9d2e)

---

## 📢 Table of Contents

- [What is the Pair Extraordinaire Badge?](#-what-is-the-pair-extraordinaire-badge)
  - [Requirements](#-requirements)
- [Step-by-Step Guide](#%EF%B8%8F-step-by-step-guide)
  - [Co-Author Commit Method](#1%EF%B8%8F⃣-co-author-commit-method)
  - [Contributor / Collaboration Method](#2%EF%B8%8F⃣-contributor--collaboration-method)
  - [IDE Method](#3%EF%B8%8F⃣-ide-method-vs-code--intellij-idea)
  - [Git CLI Method](#4%EF%B8%8F⃣-git-cli-method-terminal)
- [Screenshots](#-screenshots)
- [When Will the Badge Appear?](#%EF%B8%8F-when-will-the-badge-appear)
- [Badge Levels](#-badge-levels)
- [Important Limitations](#-important-limitations)
- [Why This Repo?](#-why-this-repo)
- [Author](#-author)

---

##  📌 What is the Pair Extraordinaire Badge?

The **Pair Extraordinaire** badge is awarded when two or more people co-author a commit that is merged into the default branch of a repository. You and your collaborator(s) will appear under that commit (via Co-authored-by) on GitHub.

- Symbol: Two people 🟢🟢 working together
- Purpose: Represents teamwork & collaboration in coding
- Unlock: ✅ Earn it by using Git’s Co-authored-by feature in commits

---

## 🔻 Requirements:

- ✅ **Co-authored commit**: The commit must contain at least one Co-authored-by: Name <email> line referencing another GitHub user.
- ✅ **Public repository (recommended)**: Using public repos is more reliably counted by GitHub. Private repos may sometimes not register the badge.
- ✅ **Verified email**: commit emails must match GitHub account emails
- ✅ **Commit pushed to default branch**: typically main or master

> ⚠️ **Important**: Just making a PR is not enough you need a commit with co-authors!

---

## 🛠️ Step-by-Step Guide

![giphy (3)](https://github.com/user-attachments/assets/de1c4e89-ab71-4705-b1b1-74a82a8ba6f0)

### 👉 Four Ways to Earn the Pull Shark Badge

---

### 1️⃣ Co-Author Commit Method

  -  Create or use a repository (public or shared)
  -  Ensure your collaborator is added as a collaborator (if it’s your repo)
  -  Create a new branch
  -  Make a commit, putting your co-author metadata properly, e.g.:

```bash

git commit -m "Add feature X for Pair Extraordinaire badge Co-authored-by: Collaborator Name <collab@example.com>"

```

  -  Push, open a pull request → merge into default branch
  -  Once merged, your co-authored commit should appear and (in many cases) trigger the badge

>  ✅ **Badge progress achieved!**

---

### 2️⃣ Contributor / Collaboration Method

  -  Fork a public project or contribute to a shared repository
  -  Work together with someone ensure they are also a collaborator (or the repo already permits them)
  -  In your commit, include Co-authored-by: … lines
  -  Submit pull request → get it merged
  -  Badge progress should increment

---

### 3️⃣ IDE Method (VS Code / IntelliJ IDEA)

-  **VS Code**:
    -  Use **GitHub Pull Requests** & **Issues extension**
    -  Add co-author in commit dialog (VS Code supports **Co-authored-by**)
    -  Commit + push → merge

-  **IntelliJ IDEA**:
    -  Commit changes → in commit message box → add co-author line manually
    -  Push → merge PR

---

###  4️⃣ Git CLI Method (Terminal)

  -  Clone repo

```bash

git clone https://github.com/your-username/github-pair-extraordinaire-badge-guide.git

cd github-pair-extraordinaire-badge-guide

```

  -  Create branch

```bash

git checkout -b pair-extraordinaire-branch

```

  -  Make change

```bash

echo "🤝 Pair Extraordinaire demo file" >> demo.txt

```

  -  Stage & commit with co-author

```bash

git add demo.txt

git commit -m "Add Pair Extraordinaire demo Co-authored-by: Friend Name <friend@example.com>"

```

  -  Push & merge → badge progress

🎯 **Done via Git CLI!**

---

## 📸 Screenshots

---

##  ⏱️ When Will the Badge Appear?

-  Usually within minutes after your commit is merged
-  In some cases, it may take up to 24 hours

>  **Note**: If it doesn’t appear → try repeating with another co-authored commit

---

## 🏅 Badge Levels

The **Pair-Extraordinaire** badge uses an "x" multiplier system:

| Level       | Requirement (co-authored merged commits)            | Badge Display          |
| ----------- | ---------------------- | ---------------------- |
| **Initial** | 1 co-authored commit   | Pair Extraordinaire x1 |
| **Bronze**  | 10 co-authored commits | Pair Extraordinaire x2 |
| **Silver**  | 24 co-authored commits | Pair Extraordinaire x3 |
| **Gold**    | 48 co-authored commits | Pair Extraordinaire x4 |

> **Note**: The "x" number indicates achievement level, not separate badge types!

---

## 🚫 Important Limitations

![giphy (5)](https://github.com/user-attachments/assets/d84c9fde-c973-4bfe-9fcd-f5d26c69a16d)

❌ **What Doesn't Count**

  -  Private repo commits
  -  Commits without Co-authored-by line
  -  Fake/non-verified emails
  -  Unmerged commits in non-default branches

---

## ⭐ Why This Repo?

  -  Helps new developers understand co-authoring commits
  -  Demonstrates the **Pair Extraordinaire** badge clearly
  -  Covers UI, IDE, and CLI workflows
  -  Encourages collaboration & open-source teamwork

✔ If this helped you → don’t forget to ⭐ star the repo!

---

## 🏆 Author

Made with ❤️ by [Sahil Sharma](https://github.com/sahil-me)

🎈 Happy contributing & badge collecting! :relaxed:
