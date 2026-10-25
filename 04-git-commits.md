# Assignment 4: Make Meaningful Git Commits

Git saves a history of changes. A commit should describe one small task.

## Set your identity

```powershell
git config --global user.name "Manan Verma"
git config --global user.email "mananverma704@gmail.com"
```

## Create a repository

Run these commands in a new practice folder:

```powershell
git init
Set-Content README.md "# My Practice Project"
git add README.md
git commit -m "docs: add project readme"
```

Make a file named `index.html`, then save it. Run:

```powershell
git add index.html
git commit -m "feat: add first html page"
```

Make a small change to `index.html`, save it and run:

```powershell
git add index.html
git commit -m "style: update page content"
git log --oneline
```

The last command shows the commit history. Do not run `git init` inside the prepared assignment repository because it already has a Git history.
