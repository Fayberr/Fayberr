### 15.12.2025
- Learned Git + Github basics
- Branches, Commit and push workflow
- Difference between staging area, commits and pushes

<details>
<summary>Git(hub) basics Recap:</summary>

- `git init`  
  Creates a local Git repository so Git can track your folders.

- `git config --global user.name "Name"`  
  `git config --global user.email "Email"`  
  Sets your name and email for commits.

- `git status`  
  Shows which files are changed, staged, or untracked.

- `git add <file>` / `git add .`  
  Adds changes to the **staging area**, ready to commit.

- `git commit -m "Message"`  
  Creates a **local snapshot** of the staged changes.

- `git remote add origin <URL>`  
  Connects your local repo to a remote (e.g., GitHub).

- `git push -u origin main`  
  Pushes local commits to the remote and sets the upstream branch.

- `git pull --rebase`  
  Fetches changes from the remote and integrates them locally without merge commits.

- `git fetch`  
  Fetches info about remote changes only, does not merge anything automatically.

- `git branch -m master main`  
  Renames your local branch.

- `.gitignore`  
  Specifies files or folders that Git should ignore.

- `.gitkeep`  
  Allows tracking of empty folders.

**Workflow in short:**  
Edit changes → `git add` → `git commit` → `git push` → version tracked locally + remotely.

</details>