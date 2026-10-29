# Lab 01: Starting a Git Repository

**Course:** HTML & CSS Development Lab (BCS554)  
**Student Name:** Mohd Javed Khan  
## Student ID :- LBCS2025023 **

---

## 🎯 Aim
Start a local Git repository inside a dedicated project folder, configure repository-specific user details, and save progress incrementally using commits.

---

## 🛠️ Tasks & Commands Executed

### Task 1: Repository Initialization & Local Configuration
Created a dedicated directory `html-lab` (or initialized inside `Lab 01`), initialized an empty Git repository, and set local configuration parameters.

```bash
# Initialize local Git repository
git init

# Set local repository identity
git config --local user.name "MohdJavedKhan"
git config --local user.email "mohdjavedkhan97587@gmail.com"

# Verify configured settings
git config user.name
git config user.email
```

---

### Task 2: Adding Initial File & First Commit
Created `index.html` with basic HTML structure, inspected repository status, tracked the file, and created the root commit.

```bash
# Check status of untracked files
git status

# Stage index.html
git add index.html

# Commit staged file
git commit -m "Add home page"
```

---

### Task 3: Modifying Content & Second Commit
Added a secondary heading (`<h2>Next Meeting</h2>`) inside `index.html`, saved changes, committed the update, and inspected commit history.

```bash
# Commit modified file directly
git commit -am "Add next meeting heading"

# View commit history in single-line format
git log --oneline
```

---

## 📁 File Structure
```text
Lab 01/
├── index.html           # HTML file with <h1> and <h2> headings
└── README.md            # Lab 01 documentation
```

---

## 📋 Terminal Output Summary
```text
e4f5g6h Add next meeting heading
a1b2c3d Add home page
```