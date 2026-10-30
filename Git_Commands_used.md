Git Commands Used

1. Git Configuration

- "git config --global user.name "Your Name"" – Sets the Git username.
- "git config --global user.email "yourmail@gmail.com"" – Sets the Git email.

2. Repository Commands

- "git init" – Initializes a new Git repository.
- "git clone <repository-url>" – Copies a remote repository to the local system.
- "git status" – Shows the current repository status.
- "git add ." – Adds all modified and new files to the staging area.
- "git add filename" – Adds a particular file to the staging area.
- "git commit -m "message"" – Saves staged changes as a commit.

3. Git History Commands

- "git log" – Displays commit history.
- "git log --oneline" – Displays commits in one-line format.
- "git log --oneline --graph --all" – Displays commit history with branches and    graph.
- "git show" – Displays details of a particular commit.

4. Git Diff Commands

- "git diff" – Shows changes in the working directory.
- "git diff --staged" – Shows changes in the staging area.
- "git diff HEAD" – Shows all changes compared with the latest commit.

5. Branching Commands

- "git branch" – Lists local branches.
- "git branch branch-name" – Creates a new branch.
- "git checkout branch-name" – Switches to another branch.
- "git switch branch-name" – Switches to another branch.
- "git switch -c branch-name" – Creates and switches to a new branch.
- "git branch -d branch-name" – Deletes a branch.

6. Merging Commands

- "git merge branch-name" – Merges another branch into the current branch.

7. Remote Repository Commands

- "git remote -v" – Displays remote repository URLs.
- "git push origin branch-name" – Pushes a branch to GitHub.
- "git pull origin branch-name" – Downloads and integrates remote changes.
- "git fetch" – Downloads remote updates without merging them.
- "git push -u origin branch-name" – Pushes a branch and sets its upstream tracking branch.

8. Git Stash Commands

- "git stash" – Temporarily saves uncommitted changes.
- "git stash list" – Displays saved stashes.
- "git stash apply" – Applies the latest stash without removing it.
- "git stash drop" – Deletes the latest stash.

9. Git Reset Commands

- "git reset --soft HEAD~1" – Removes the latest commit but keeps changes staged.
- "git reset --mixed HEAD~1" – Removes the latest commit and unstages changes.

10. Git Revert Commands

- "git revert commit-id" – Creates a new commit that reverses the changes of a previous commit.

11. Git Ignore Commands

- ".gitignore" – Specifies files and folders Git should ignore.

