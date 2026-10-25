<!-- A. Check repository status and information
Command	What it does
git status	Shows changed, staged, and untracked files
git status -sb	Short status, including branch information
git log	Shows commit history
git log --oneline	Shows compact commit history
git log --oneline --graph --all	Shows branch history as a graph
git show	Displays the latest commit and its changes
git show COMMIT_ID	Displays a particular commit
git diff	Shows unstaged changes
git diff --staged	Shows staged changes
git diff A..B	Compares two revisions
git ls-files	Lists files tracked by Git
git rev-parse --is-inside-work-tree	Checks whether you're inside a working repository

B. Stage and commit changes
Command	What it does
git add file.py	Stages a particular file
git add file1.py file2.py	Stages selected files
git add .	Stages changes under the current directory
git add -A	Stages additions, modifications, and deletions across the working tree
git add -p	Interactively stages selected chunks of changes
git commit -m "message"	Creates a commit
git commit	Opens an editor to write the commit message
git commit --amend	Replaces the latest commit with a revised one
git commit --amend --no-edit	Amends the latest commit without changing its message
git rm file.py	Removes a tracked file and stages its deletion
git mv old.py new.py	Moves or renames a tracked file -->
<!-- C. Connect and synchronize with GitHub
Command	What it does
git remote -v	Shows remote URLs
git remote add origin URL	Adds a remote named origin
git remote set-url origin URL	Changes the remote URL
git remote remove origin	Removes the remote configuration
git fetch origin	Downloads remote updates without merging them into your current branch
git pull	Fetches and integrates updates from the configured upstream
git pull --rebase	Fetches updates and rebases your local commits on top
git push	Uploads local commits
git push -u origin main	Pushes main and sets its upstream
git push origin branch-name	Pushes a specific branch
git push --all origin	Pushes local branches
git push --tags	Pushes tags -->
<!-- Fetch brings information from GitHub to your local repository. Push sends your committed changes from your local repository to GitHub. -->
<!-- git fetch → Get information about remote updates.
git pull → Fetch updates and integrate them into your current branch.
git push → Upload your commits.
git clone → Download a repository to create a local copy. -->