\# Git Command Notes



\## 1. git init

Initializes a new Git repository.



Example:

git init



\## 2. git clone

Copies an existing remote repository to your computer.



Example:

git clone https://github.com/username/repository.git



\## 3. git status

Shows the current status of files in the repository.



Example:

git status



\## 4. git add

Stages files for the next commit.



Example:

git add README.md



\## 5. git commit

Saves staged changes as a commit.



Example:

git commit -m "Add README documentation"



\## 6. git log

Displays the commit history.



Example:

git log --oneline



\## 7. git diff

Displays unstaged changes made to tracked files.



Example:

git diff



\## 8. git push

Uploads local commits to a remote repository.



Example:

git push origin main



\## 9. git pull

Downloads and integrates changes from a remote branch.



Example:

git pull origin main



\## 10. git fetch

Downloads information about remote changes without integrating them.



Example:

git fetch origin



\## 11. git branch

Lists existing branches.



Example:

git branch



\## 12. git switch

Switches to another branch or creates a new branch.



Example:

git switch -c feature-documentation



\## 13. git merge

Combines changes from another branch into the current branch.



Example:

git merge feature-documentation



\## 14. git remote

Displays the remote repositories connected to your local repository.



Example:

git remote -v

## Git Branching Practice



\### Create a new branch

git switch -c feature/example



\### List branches

git branch



\### Push a branch to GitHub

git push -u origin feature/example



\### Check repository status

git status



\### View commit history

git log --oneline



\### Conclusion

Git branches allow developers to work on separate features without

making changes directly to the main branch.

