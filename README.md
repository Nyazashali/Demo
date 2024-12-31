# Demo
This is my git repository
<br>
Author - Shaik Nyazash Ali

----Setup and Configuration----
git config: Configure user information, like name and email.
git config --global user.name "Your Name"
git config --global user.email "youremail@example.com"
git init: Initialize a new Git repository in the current directory.

git init
Basic Workflow
git status: Check the status of your repository (changes, staged files, etc.).

git status
git add: Stage changes for the next commit.

git add <file>
git add .  # Stage all changes
git commit: Commit staged changes with a message.


git commit -m "Your commit message"
git log: View the commit history.

git log
git log --oneline  # Compact view
Branching
git branch: List branches or create a new branch.

git branch           # List branches
git branch <branch-name>  # Create a new branch
git checkout: Switch to another branch.

git checkout <branch-name>
git switch: Alternative command for switching branches.

git switch <branch-name>
git merge: Merge a branch into the current branch.

git merge <branch-name>
git branch -d: Delete a branch.

git branch -d <branch-name>
Remote Repositories
git clone: Clone a repository to your local machine.

bash
Copy code
git clone <repository-url>
git remote: Manage remote repositories.

bash
Copy code
git remote -v  # View remotes
git remote add origin <repository-url>  # Add a remote repository
git push: Push commits to a remote repository.

bash
Copy code
git push origin <branch-name>
git pull: Fetch and merge changes from a remote repository.

bash
Copy code
git pull origin <branch-name>
git fetch: Fetch changes from a remote repository without merging.

bash
Copy code
git fetch origin
Undoing Changes
git reset: Unstage changes or reset commits.

bash
Copy code
git reset <file>  # Unstage a file
git reset --soft <commit>  # Reset to a commit but keep changes staged
git reset --hard <commit>  # Reset to a commit and discard changes
git restore: Discard changes in the working directory.

bash
Copy code
git restore <file>  # Discard changes to a file
git restore --staged <file>  # Unstage a file
Stashing
git stash: Temporarily save uncommitted changes.

bash
Copy code
git stash
git stash apply: Reapply the stashed changes.

bash
Copy code
git stash apply
git stash pop: Apply and remove stashed changes.

bash
Copy code
git stash pop
Tags
git tag: Create or list tags.

bash
Copy code
git tag <tag-name>  # Create a tag
git tag             # List tags
git push origin <tag-name>: Push a tag to a remote repository.

bash
Copy code
git push origin <tag-name>
These commands are sufficient for most Git workflows. As you get more comfortable, you can explore advanced features like rebasing, squashing commits, and resolving merge conflicts.