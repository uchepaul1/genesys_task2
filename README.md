# genesys_task2
# Version Control Basics

## What is Version Control?
Version control is a system that records changes to a file or set of files over time. It allows you to recall specific versions later, collaborate with others, and maintain an organized history of your project.

---

## Difference Between Git and GitHub

- **Git**:
  - A version control tool used to manage local repositories.
  - Works offline and handles the creation, management, and tracking of changes in files.
  
- **GitHub**:
  - A web-based platform for hosting Git repositories online.
  - Provides collaboration features such as pull requests, issue tracking, and more.

---

## Alternatives to GitHub
1. **GitLab** - An open-source DevOps platform.
2. **Bitbucket** - A Git repository hosting service by Atlassian.
3. **SourceForge** - A platform for hosting and distributing software projects.

---

## Difference Between `git fetch` and `git pull`

- **`git fetch`**:
  - Downloads changes from the remote repository but does not merge them into your working branch.
  
- **`git pull`**:
  - Downloads changes from the remote repository and merges them into your working branch.

---

## What is `git rebase`?

- **`git rebase`**: Reorganizes commits by moving them to the top of another branch.
- **Command**:
  ```bash
  git rebase <branch_name>

## What is `git cherry-pick`?

- **`git cherry-pick`**: Applies a specific commit from one branch to another.  
  This is useful when you want to integrate specific changes from one branch into another without merging the entire branch.

### **Command**:
```bash
git cherry-pick <commit_hash>

