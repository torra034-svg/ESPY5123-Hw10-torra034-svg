# GitHub Desktop Cheat Sheet (Beginner Version)

## What problem does GitHub Desktop solve?
GitHub Desktop helps you **save versions of your work**, **undo mistakes**, and **turn in or share code** without using the command line.

Think of it like **track changes + backups** for your project.

---

## The basic idea (90 second mental model)

- Your **project folder** lives on your computer  
- GitHub Desktop **watches that folder**  
- You occasionally:
  1. Save your changes
  2. Add a short note about what you did
  3. Push a copy to GitHub

That’s it.

---

## Everyday workflow (this is the loop)

### 1. Open your project
- Open **GitHub Desktop**
- Select your repository from the left sidebar
- Open the project in RStudio if you are working in R

---

### 2. Make changes like normal
- Edit files
- Save them
- Do your work
- Nothing special yet

---

### 3. Check what changed
In GitHub Desktop:
- Click your repository
- Click the **Changes** tab
- You will see a list of files you edited
- Click a file to preview what changed

This is just a preview. Nothing is saved yet.

---

### 4. Commit your changes (save a version)
At the bottom left:
- Write a **short message** describing what you did  

Examples:
- `Fix data import`
- `Add comments to analysis`
- `Update plot labels`

- Click **Commit to main**

A commit is just a labeled snapshot of your project.

---

### 5. Push to GitHub (backup and share)
After committing:
- Click **Push origin** at the top

This uploads your changes to GitHub so they are backed up and visible to others.

---

## What buttons do I actually need?

| Button        | What it does |
|--------------|--------------|
| Changes       | Shows what files you edited |
| Commit        | Saves a snapshot of your work |
| Push origin   | Uploads your commits to GitHub |
| Pull origin   | Downloads updates from GitHub |

If you can find these four, you’re good.

---

## When should I commit?

Good times to commit:
- Something works now
- You finished a task
- You want a safe restore point
- You are about to try something risky

You do **not** need to commit after every tiny edit.

---

## Writing good commit messages

Bad:
- `stuff`
- `changes`
- `update`

Better:
- `Clean up variable names`
- `Fix error in loop`
- `Add draft results section`

Rule of thumb:  
**Future you should understand what changed.**

---

## Common beginner questions

**Did I break anything by committing?**  
No. Commits are reversible.

**Can I undo a commit?**  
Yes. That is one of the main reasons we use git.

**What if I forget to push?**  
Your work is safe locally, but it is not backed up online yet.

**What if GitHub Desktop looks scary?**  
You are probably just looking at the Changes tab. That is normal.

---

## Things you can safely ignore (for now)

- Branches  
- Merging  
- Rebasing  
- Conflicts  
- Command line git  

We will tell you when these matter.

---

## One-sentence summary
**Edit files → Commit with a message → Push to GitHub**
