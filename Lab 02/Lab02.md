# Lab 02: Pushing and Cloning a Repository

**Course:** HTML & CSS Development Lab (BCS554)  
**Student Name:** Mohd Javed Khan 
## Student ID :- LBCS2025023 ** 

---

## 🎯 Aim
Set up a local bare repository acting as a remote origin, push commits from the working repository to the bare repository, and clone it into a secondary folder to verify remote synchronization.

---

## 🛠️ Tasks & Commands Executed

### Task 1: Bare Repository Initialization & Remote Linking
Created an empty bare Git repository `html-remote` adjacent to `Lab 01`, added it as a remote named `origin`, and verified configured remote URLs.

```bash
# Initialize bare repository next to current folder
git init --bare ../html-remote

# Link local repository to bare remote repository
git remote add origin ../html-remote

# Verify remote configuration
git remote -v
```

---

### Task 2: Pushing Local Commits to Remote
Pushed local commits on branch `master` (or `main`) to the linked bare origin.

```bash
# Push master branch commits to origin
git push origin master
```

---

### Task 3: Cloning Remote Repository
Navigated up one directory level, cloned `html-remote` into a new folder named `html-copy`, navigated into `html-copy`, and inspected commit log to verify exact history replication.

```bash
# Move to parent directory
cd ..

# Clone bare repository into html-copy
git clone html-remote html-copy

# Navigate into cloned directory
cd html-copy

# Verify synced history
git log --oneline
```

---

## 📁 File Structure
```text
BCS554-HTML-CSS-Lab/
├── html-remote/         # Bare Git repository acting as remote server
├── html-copy/           # Cloned repository instance
├── Lab 01/              # Original working repository
└── Lab 02/
    └── README.md        # Lab 02 documentation
```