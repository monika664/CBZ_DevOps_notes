# CBZ_DevOps_notes
Here’s a list of the most useful Git commands with explanations for each:

### 1. **Basic Commands**
   - **`git init`**: Initializes a new Git repository in the current directory.
   - **`git clone <url>`**: Copies an existing repository from a URL to your local machine.
   - **`git status`**: Shows the status of changes as untracked, modified, or staged.
   - **`git add <file>`**: Stages changes for the next commit.
   - **`git commit -m "message"`**: Commits staged changes with a descriptive message.
   - **`git log`**: Shows the commit history.
   - **`git diff`**: Shows changes between working directory and staging area.

### 2. **Branching and Merging**
   - **`git branch`**: Lists all branches in your repository. The current branch is marked with an asterisk.
   - **`git branch <branch-name>`**: Creates a new branch.
   - **`git checkout <branch-name>`**: Switches to the specified branch.
   - **`git merge <branch-name>`**: Merges the specified branch into the current branch.
   - **`git branch -d <branch-name>`**: Deletes the specified branch if it has been merged.

### 3. **Remote Repositories**
   - **`git remote -v`**: Shows the URLs of remote repositories.
   - **`git fetch <remote>`**: Fetches changes from a remote repository but does not merge them.
   - **`git pull <remote> <branch>`**: Fetches changes from a remote branch and merges them into your current branch.
   - **`git push <remote> <branch>`**: Pushes your commits to the specified branch of the remote repository.
   - **`git remote add <name> <url>`**: Adds a new remote with a name and URL.

### 4. **Undoing Changes**
   - **`git reset <file>`**: Unstages a file, keeping its changes.
   - **`git checkout -- <file>`**: Discards changes in the working directory.
   - **`git reset --hard <commit>`**: Resets the repository to a specific commit, discarding all changes after that commit.
   - **`git revert <commit>`**: Creates a new commit that undoes a specific commit.

### 5. **Stashing**
   - **`git stash`**: Saves changes in a "stash" so you can work on something else.
   - **`git stash apply`**: Applies the most recent stash to the working directory.
   - **`git stash list`**: Lists all stashes.
   - **`git stash pop`**: Applies and then deletes the most recent stash.

### 6. **Tagging**
   - **`git tag <tagname>`**: Creates a tag at the current commit.
   - **`git tag`**: Lists all tags in the repository.
   - **`git push <remote> <tagname>`**: Pushes a specific tag to a remote repository.

### 7. **Advanced Commands**
   - **`git rebase <branch>`**: Reapplies commits on top of another base commit.
   - **`git cherry-pick <commit>`**: Applies a specific commit from one branch to another.
   - **`git clean -fd`**: Removes untracked files and directories from the working directory.

### 8. **Collaborative Commands**
   - **`git pull --rebase`**: Rebases commits on top of changes from a remote branch, reducing merge conflicts.
   - **`git blame <file>`**: Shows who last modified each line in a file.

These commands cover most day-to-day Git tasks, helping you manage your project effectively.
