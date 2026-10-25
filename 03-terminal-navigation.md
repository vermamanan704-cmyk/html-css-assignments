# Assignment 3: Terminal Navigation Practice

Use the VS Code terminal on Windows. These commands work in PowerShell.

1. Show the current folder: `pwd`
2. List files: `Get-ChildItem`
3. Show hidden files: `Get-ChildItem -Force`
4. Create a folder: `mkdir practice`
5. Enter the folder: `cd practice`
6. Create a file: `New-Item index.html -ItemType File`
7. Create a CSS folder: `mkdir css`
8. Go up one folder: `cd ..`
9. Go to your home folder: `cd ~`
10. Copy a file: `Copy-Item index.html backup.html`
11. Rename a file: `Rename-Item backup.html old.html`
12. Delete a file: `Remove-Item old.html`
13. Delete a folder: `Remove-Item css -Recurse`
14. Read a file: `Get-Content index.html`
15. Clear the terminal: `Clear-Host`
16. Open the current folder in VS Code: `code .`

## Practice task

Create a folder named `website`. Inside it, create `index.html`, a folder named `css` and a folder named `images`. Use `Get-ChildItem` to check the files. Then open the `website` folder in VS Code with `code .`.
