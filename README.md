# CS50W: Web Programming with Python and JavaScript
## Lecture 0: Git & Version Control

Welcome to the **CS50W Lecture 0** reference repository. This module introduces essential version control concepts using **Git** and **GitHub**, preparing you for building, collaborating on, and deploying web applications.

---

## 📌 Topics Covered

- **Introduction to Version Control Systems (VCS)**: Why tracking changes and keeping history matters.
- **Collaboration & Synchronization**: Merging work, handling remote repositories, and resolving team workflows.
- **Core Git Commands**: From initializing a repo to staging, committing, and pushing.
- **GitHub & Remote Repositories**: Linking local projects with remote platforms.
- **Deployment via GitHub Pages**: Hosting static HTML/CSS web pages directly on the web.

---

## 🛠️ Essential Git Commands Reference

### 1. Repository Setup & Status

| Command | Description |
| --- | --- |
| `git init` | Initializes a new Git repository in the current directory. |
| `git clone <URL>` | Downloads a copy of an existing remote repository to your local machine. |
| `git status` | Displays the status of the working directory and staging area (untracked, modified, or staged files). |
| `git log` | Shows the history of commits in the current branch. |

---

### 2. Making Changes & Snapshotting

| Command | Description |
| --- | --- |
| `git add <file>` | Stages a specific file for the next commit. |
| `git add .` | Stages all modified and new files in the current directory. |
| `git commit -m "Your commit message"` | Saves a snapshot of staged changes to the repository history with a descriptive message. |
| `git diff` | Shows differences between working files and the last commit or staging area. |

---

### 3. Syncing with Remote Repositories (GitHub)

| Command | Description |
| --- | --- |
| `git remote add origin <URL>` | Connects your local repository to a remote GitHub repository named `origin`. |
| `git push -u origin master` | Uploads local commits to the `master` (or `main`) branch on the remote repository. |
| `git pull` | Fetches changes from the remote repository and merges them into the current local branch. |

---

### 4. Branching & Merging

| Command | Description |
| --- | --- |
| `git branch` | Lists all local branches. |
| `git branch <branch-name>` | Creates a new branch. |
| `git checkout <branch-name>` | Switches to the specified branch. |
| `git merge <branch-name>` | Combines changes from the specified branch into the current active branch. |

---

## 🌐 Deploying to GitHub Pages

GitHub Pages allows you to host static web content (HTML, CSS, JavaScript) directly from your repository.

1. Push your website files (e.g., `index.html` or `hello.html`) to the `master` / `main` branch.
2. Go to your repository on GitHub → **Settings**.
3. Scroll down to the **GitHub Pages** section.
4. Under **Source**, select the `master` / `main` branch and click **Save**.
5. Access your live site at:
   ```text
   https://<your-username>.github.io/<repository-name>/<file.html>
