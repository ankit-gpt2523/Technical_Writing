# GIT AND GITHUB

## 1. Introduction

Git is a distributed version control system used to track changes in files and manage different versions of a project.

GitHub is a cloud-based platform that allows developers to host Git repositories, share code, and collaborate on software projects.

## 2. Git

### 2.1 Features of Git

- Tracks changes in files.
- Maintains project history.
- Supports branching and merging.
- Allows recovery of previous versions.
- Supports collaborative development.

### 2.2 Important Git Commands

| Command | Description |
|---|---|
| `git init` | Initializes a repository |
| `git status` | Shows repository status |
| `git add .` | Stages all changes |
| `git commit -m "message"` | Saves changes |
| `git log` | Displays commit history |
| `git branch` | Lists branches |
| `git switch branch` | Switches branches |
| `git merge branch` | Merges branches |
| `git clone URL` | Copies a remote repository |

### 2.3 Basic Git Workflow

Git follows three main stages:

1. **Working Directory:** Files are created or modified.
2. **Staging Area:** Changes are selected using `git add`.
3. **Repository:** Changes are saved using `git commit`.

Example:

```bash
git init
git add .
git commit -m "Initial commit"
```

## 3. GitHub

### 3.1 Features of GitHub

- Online repository hosting.
- Public and private repositories.
- Collaboration among developers.
- Pull requests and code reviews.
- Issue tracking.
- Project documentation through README files.

### 3.2 Important GitHub Concepts

- **Repository:** Storage location for project files.
- **Fork:** A personal copy of another user's repository.
- **Clone:** Creates a local copy of a remote repository.
- **Pull Request:** Requests merging changes into another branch.
- **Issues:** Used to report bugs and track tasks.

### 3.3 Connecting Git to GitHub

The following commands connect a local Git repository to GitHub:

```bash
git remote add origin <repository-url>

git branch -M main

git push -u origin main
```

### 3.4 Important Commands

| Command | Description |
|---|---|
| `git remote -v` | Shows remote repository URLs |
| `git push` | Uploads committed changes |
| `git pull` | Downloads and integrates remote changes |
| `git fetch` | Downloads remote changes |
| `git clone URL` | Downloads a repository |

## 4. Difference Between Git and GitHub

| Git | GitHub |
|---|---|
| Version control system | Online hosting platform |
| Works locally | Provides cloud storage |
| Tracks file changes | Hosts Git repositories |
| Manages commits and branches | Supports collaboration and pull requests |

## 5. Applications

- Managing software projects.
- Tracking code modifications.
- Team collaboration.
- Open-source development.
- Maintaining project history.
- Sharing academic and personal projects.

## 6. Conclusion

Git and GitHub are essential tools in modern software development. Git helps manage versions and track changes, while GitHub provides an online platform for hosting repositories and collaborating with other developers. Together, they make software development more organized and efficient.