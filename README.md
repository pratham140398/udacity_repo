# udacity_repo
This is a repository to gain familiarity with git and GitHub.


git init: Initializes a new, empty Git repository in your current directory.
git clone [url]: Creates a local copy of a remote repository.
git config --global user.name "[name]": Sets your name for commit identification.2. The Core Workflow (Stage & Commit)Use these daily to track and save your work.
git status: Shows which files are modified, staged, or untracked.
git add [file]: Adds specific files to the staging area to prepare for a commit.
git add .: Stages all changed and new files in the repository.
git commit -m "[message]": Permanently saves the staged changes to the version history with a descriptive message.3. Branching & MergingThese allow you to work on features in isolation.
git branch: Lists all local branches in the repository.
git branch [branch-name]: Creates a new branch.
git switch [branch-name] or 
git checkout [branch-name]: Switches to the specified branch.
git switch -c [branch-name]: Creates a new branch and switches to it immediately.
git merge [branch]: Integrates the specified branch's history into your current branch.4. Remote SyncingThese commands connect your local work to servers like GitHub or GitLab.
git remote add origin [url]: Links your local repository to a remote server.
git pull: Fetches changes from the remote repository and merges them into your local branch.
git push origin [branch]: Uploads your local commits to the remote repository.
git fetch: Downloads content from a remote repository without merging it into your local code.5. Inspection & Undoing ChangesUseful for reviewing history or fixing mistakes.
git log: Displays the full commit history for the current branch.
git diff: Shows the differences between your current working directory and the staging area.
git stash: Temporarily saves modified, tracked files so you can work on something else without committing.
git reset --hard [commit-id]: Resets your working directory and history to a specific commit, discarding all changes after it
git revert [commit-id]: Creates a new commit that undoes the changes of a previous commit without deleting its history.

gti checkout -b <brach_name>: create a new brach and switch to that brach