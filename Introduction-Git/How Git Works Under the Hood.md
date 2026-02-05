# 🛠️ How Git Works Under the Hood (Simple Explanation)

## 📌 Introduction

Git is a **Version Control System** that tracks changes in files and helps developers manage project history.  
Behind the scenes, Git does not just save files — it saves **snapshots** of your project.

---

## 🧠 Basic Idea of Git

Git works like a **time machine** for your code.

Instead of saving only changes, Git saves the **complete snapshot** of files every time you commit.

---

## 🗂️ Main Components of Git

Git mainly works using three important areas:

### 1️⃣ Working Directory

👉 This is your project folder.

- Where you create and edit files
- Changes are not saved in Git yet
- Example: Writing or editing code in VS Code

---

### 2️⃣ Staging Area (Index)

👉 This is a preparation area.

- Stores selected changes before committing
- Allows you to choose which changes to save

#### Command Used

---

### 3️⃣ Repository (.git Folder)

👉 This is Git’s brain.

- Stores project history
- Saves commits
- Tracks changes
- Hidden folder inside your project

---

## 🔄 Git Workflow

Working Directory → Staging Area → Repository

### Step 1: Modify Files

You create or edit files.

### Step 2: Add Files

git add file_name

Moves changes to staging area.

### Step 3: Commit Changes

git commit -m "Message"

Git saves a snapshot of your project.

---

## 📦 How Git Stores Data

Git stores data as **Snapshots**, not file differences.

Each commit contains:

- File data
- Commit message
- Author name
- Timestamp
- Unique ID (Hash)

---

## 🔐 Git Uses Hashing

Git uses a **SHA (Secure Hash Algorithm)**.

- Every commit gets a unique ID
- Helps track changes safely
- Prevents data corruption

Example:

a3f5d2e8c4b1...

---

## 🌿 How Branching Works

Branch = Separate version of code.

Git creates branches by:

- Creating pointers to commits
- Lightweight and fast
- Allows parallel development

Example:

Main Branch → Stable Code
Feature Branch → New Feature

---

## 🔗 How Git Tracks Changes

Git tracks changes using:

- File snapshots
- Commit history
- References (branches and tags)

---

## ☁️ Local vs Remote Repository

### Local Repository

Stored on your computer.

### Remote Repository

Stored on platforms like GitHub.

Commands:

git push → Upload code
git pull → Download code

---

## 🎯 Why Git is Fast

Git is fast because:

- Works locally
- Uses snapshots
- Uses compressed storage
- Uses hashing for quick tracking

---

## 📝 Simple Real-Life Example

Imagine writing notes in a notebook:

- Working Directory → Writing notes
- Staging Area → Selecting pages to save
- Repository → Final saved notebook versions

---

## ✅ Conclusion

Git works by saving snapshots of your project, tracking changes, and maintaining history.  
It uses staging areas, repositories, hashing, and branching to manage code efficiently.
