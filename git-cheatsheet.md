### Configuration
- `git config --global user.name "Your Name"`: Set your username globally.
- `git config --global user.email "youremail@example.com"`: Set your email globally.

### Creating Repositories
- `git init`: Initialize a new Git repository in the current directory.
- `git clone <repository_url>`: Clone an existing repository from a URL.

### Basic Commands
- `git status`: Check the status of your working directory and staging area.
- `git add <file>`: Add a file to the staging area.
- `git commit -m "Commit message"`: Commit changes in the staging area with a message.
- `git push`: Push commits to a remote repository.
- `git pull`: Fetch changes from a remote repository and merge them into your local branch.

### Branching and Merging
- `git branch`: List all local branches.
- `git branch <branch_name>`: Create a new branch.
- `git checkout <branch_name>`: Switch to a different branch.
- `git merge <branch_name>`: Merge changes from a specified branch into the current branch.

### Inspecting History
- `git log`: View commit history.
- `git diff`: Show changes between commits, commit and working tree, etc.

### Undoing Changes
- `git reset HEAD <file>`: Unstage changes in a file.
- `git checkout -- <file>`: Discard changes in a file in the working directory.
- `git revert <commit>`: Revert a commit by creating a new commit with the inverse changes.

### Remote Repositories
- `git remote -v`: List all remote repositories.
- `git remote add <name> <url>`: Add a new remote repository.
- `git remote remove <name>`: Remove a remote repository.
