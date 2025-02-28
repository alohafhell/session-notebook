<h2> Basic Branch Commands:</h2>
<h3>Create a New Branch:</h3>

<code>git checkout -b branch-name'</code>

Creates a new branch and switches to it.

<h3>Switch Between Branches:</h3>

<code>git checkout branch-name </code>
Switches to an existing branch.

<h3>List All Branches:</h3>

<code>git branch</code>
Shows all branches, with the current branch highlighted.

<h3>Delete a Branch (after merging):</h3>

<code>git branch -d branch-name</code>
Deletes the branch you no longer need.

<h3>Merge a Branch into Main:</h3>

<code>git checkout main</code>
<code>git merge branch-name</code>
Switches to the main branch and merges changes from your feature branch.

<h3>Commit and Sync Changes:

<h3>Check the Status of Your Branch:</h3>

<code>git status</code>
Shows what changes have been made and not yet committed.

<h3>Stage Changes for Commit:</h3>

<code>git add .</code>
Adds all modified files to the staging area, preparing them for commit.

<h3>Commit Changes with a Message:</h3>

<code>git commit -m "Your commit message"</code>
Saves changes with a short description of what you did.

<h3>Push Your Changes to GitHub:</h3>

<code>git push origin branch-name</code>
Uploads your branch and changes to GitHub.

<h3>Collaborating & Pulling Changes:</h3>

<h3>Fetch and Merge Changes from GitHub:</h3>

<code>git pull origin main</code>
Pulls down changes from the remote main branch and merges them into your local copy.

<h3>Clone a GitHub Repository:</h3>

<code>git clone repository-link</code>

Copies a GitHub repository to your local machine.

<h2>Miscellaneous</h2>

<h3>Check Log of Commits:</h3>

<code>git log</code>
Shows a history of all the commits in your branch.

<h3>Stash Temporary Changes (if you’re not ready to commit):</h3>

<code>git stash</code>
Temporarily hides uncommitted changes and cleans your workspace.

<h3>Apply Stashed Changes:</h3>

<code>git stash apply</code>
Applies stashed changes back to your working directory.

<h3>Undo a Commit (before pushing):</h3>

<code>git reset --soft HEAD~1</code>
Undoes the last commit but keeps your changes (safe if you made a mistake).

<h3>Short Hints:</h3>
Branching is your friend: Always create a branch before starting new work to keep your main branch safe.
Commit often: Save your progress regularly with meaningful commit messages.

<h3>Sync frequently:</h3> 
Use <code>git pull</code> and <code>git push</code> to keep your local and remote branches in sync with others.

<h3>Pull requests (PRs):</h3>
 Before merging into the main branch on GitHub, consider creating a pull request for review.
