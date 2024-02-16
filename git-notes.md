`git init`: Initializes a new Git repository. This command creates a new .git directory in your project, which Git uses to track changes.

`git clone <repository-url>`: Creates a local copy of a remote repository. This command is used when you want to work on an existing project that is hosted on a server (e.g., GitHub, GitLab).

`git add <file>`: Adds files to the staging area. It tells Git that you want to include updates to a particular file(s) in the next commit. Use git add . to add all changed files to the staging area.

`git commit -m "Your commit message"`: Records or snapshots the file permanently in the version history along with a message from the user describing the changes.

`git status`: Shows the status of changes as untracked, modified, or staged.

`git log`: Displays the committed history, allowing you to see the previous commits.

`git push <remote> <branch>`: Uploads all local branch commits to the remote repository. <remote> is typically origin, and <branch> is your current branch.

`git pull <remote> <branch>`: Fetches the changes from the remote repository to your current branch and merges them. This command is a combination of git fetch followed by git merge.

`git branch`: Lists all the local branches in your repository. Use `git branch <branch-name>` to create a new branch, and `git branch -d <branch-name>` to delete a branch.

`git checkout <branch-name>`: Switches to the specified branch and updates the working directory to match. Use `git checkout -b <branch-name>` to create and switch to a new branch.

`git merge <branch>`: Merges the specified branch into the current branch. This command is used to combine changes from one branch into another.

`git diff`: Shows the differences between files in the working directory and the staging area.

`git reset`: Resets your index and working directory to the state of your last commit. This is useful for undoing changes. Use carefully.

`git stash`: Temporarily shelves (or stashes) changes so you can work on a different branch without committing incomplete work on your current branch.
