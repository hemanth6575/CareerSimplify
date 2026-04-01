# Git vs GitHub

## 1. Key Differences

### Git
1. Git is a **version control system** used to track changes in source code.
2. It works mainly through the **command line (terminal)**.
3. It is a **software/tool** installed on your local machine.
4. It allows you to **manage and track code versions locally**.
5. It does **not require internet** for most operations.

### GitHub
1. GitHub is an **online platform** used to host Git repositories.
2. It provides a **GUI (web interface)** and tools like GitHub Desktop.
3. It is a **cloud-based service** built on top of Git.
4. It allows **collaboration, code sharing, and version management online**.
5. It **requires internet** for accessing remote repositories.

---

## One-Line Difference

- **Git** → Tool to track code changes  
- **GitHub** → Platform to store and share code online

## 2. Why We Use Git & GitHub in Team Projects

1. **Collaboration**
   - Multiple developers can work on the same project at the same time without conflicts.

2. **Version Control**
   - Keeps track of all changes made to the code.
   - Allows reverting to previous versions if something breaks.

3. **Branching**
   - Developers can create separate branches to work on features or fixes without affecting the main code.

4. **Code Review**
   - Team members can review each other’s code using pull requests before merging.

5. **Backup & Security**
   - Code is stored safely in remote repositories (GitHub), reducing risk of data loss.

6. **Conflict Management**
   - Git helps identify and resolve conflicts when multiple people edit the same file.

7. **Project Tracking**
   - GitHub provides features like issues, discussions, and project boards to manage tasks.

---

## Simple Explanation

- Git helps manage code changes.
- GitHub helps teams work together on that code.



## 3 .Basic Workflow

### Step-by-Step Git Workflow

1. **Clone the Repository**
   - Copy the remote repository to your local machine.
   - Example: `git clone <repo-url>`

2. **Make Changes**
   - Edit, add, or delete files in your project.

3. **Add Changes (Staging)**
   - Move changes to the staging area.
   - Example: `git add .`

4. **Commit Changes**
   - Save the changes with a meaningful message.
   - Example: `git commit -m "Added new feature"`

5. **Push Changes**
   - Upload your changes to the remote repository (GitHub).
   - Example: `git push origin main`

---

## Simple Flow

`clone → make changes → add → commit → push`
