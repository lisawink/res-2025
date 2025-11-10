# Instructions: Submit Your Mini Project via GitHub Pull Request

In this exercise, you will fork the course repository, add your completed mini project (Overleaf paper + Inkscape figure), and submit a **Pull Request (PR)** to a branch in the main repository named after you. This allows me to review your work and keeps the main repository organized.

---

## 1. Fork the Repository

1. Go to the course repository: [[res-2025] ](https://github.com/lisawink/res-2025) 
2. Click the **Fork** button in the top right.  
3. This creates a copy of the repository in your GitHub account.

---

## 2. Clone Your Fork Locally

Open a terminal and run:

```
git clone https://github.com/YOUR_USERNAME/res-2025.git
cd res-2025
```

---

## 3. Create a Branch Named After You

```
git checkout -b student-YOURNAME
```
Important: All your changes must be committed to this branch. Do not make changes on main.

---

## 4. Add Your Files

1. Add your Overleaf project files (main.tex, references.bib, etc.)
2. Add your Inkscape figure (figure.pdf)
3. Update the README.md if needed

Check your status:
```
git status
```

---

## 5. Stage and Commit Your Changes

```
git add .
git commit -m "Added mini project files"
```
The . stages all modified and new files.

Use a clear commit message describing your work.

---

## 6. Push Your Branch to Your Fork

```
git push origin student-YOURNAME
```
Replace YOURNAME with your branch name.

---

## 7. Create a Pull Request (PR)

1. Go to your fork on GitHub
2. Click Compare & pull request
3. Ensure the PR is set to merge into this repository, into a branch called student-YOURNAME.
4. Write a short description e.g. “Mini project submission: Overleaf paper + figure”
5. Submit the PR
Note: Do not request to merge into main. Always target a branch named after you.

---

## 8. Verify Your Submission

Check that your PR contains:
- main.pdf
- main.tex
- references.bib
- figure.pdf
- Optional updates to README.md

---

## Tips:
1. Commit early and often; each commit is a snapshot of your progress.
2. Use descriptive branch names (e.g., student-alicej) to avoid conflicts.
3. GitHub’s web interface can be used for simple edits if you prefer not to use the terminal.


UPDATE:
We completed the tasks in class and have now figured out how to fork the repository and commit and push our changes to it. See you next week!