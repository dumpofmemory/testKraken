# Terminal Commands

- **touch** _<filename>_ - creates a new file
- **mv** _<oldfilename>_ _<newfilename>_ - renames file
- **mkdir** - creates a directory
- **rm** - removes

# Git


$ git config --global user.name "Gregg Pollack"
$ git config --global user.email gregg@codeschool.com
$ git config --global color.ui true

- **git init** Initialized empty Git repository in /Users/sam/store/.git/
- **git add --all**
- **git rm --cached <filename>**
- **git status**
- **git commit -m "Create a README."**
- **git log**
- "git checkout -- <filename>..." to discard changes in working directory
- **git diff** show unstaged differences since last commit
- **git diff --staged**
- **git reset HEAD LICENSE** refers to last commit and will unstage it
- **git checkout -- LICENSE** blow away all changes since last commit

## SKIP STAGING AND COMMIT

git commit -a -m "Modify readme" Add changes from all tracked files. Doesn’t add new (untracked) files