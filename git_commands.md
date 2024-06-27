# Initialize a new Git repository in the current directory
git init

# Add files to the staging area for commit
git add <file_name>

# Add all files in the current directory to the staging area
git add .

# Commit changes in the staging area with a message
git commit -m "Your commit message"

# Push changes to a remote repository (e.g., GitHub)
git push <remote_name> <branch_name>

# Pull changes from a remote repository (e.g., GitHub)
git pull <remote_name> <branch_name>

# Clone an existing repository from a remote server
git clone <repository_url>

# Create a new branch
git branch <branch_name>

# Switch to a different branch
git checkout <branch_name>

# Merge one branch into another
git merge <branch_name>

# List all branches
git branch

# Delete a branch
git branch -d <branch_name>

# Show the commit history
git log

# Show the changes made in a specific commit
git show <commit_hash>

# Reset the current branch to a specific commit
git reset --hard <commit_hash>

# Revert a specific commit and create a new commit with the changes
git revert <commit_hash>

# Stash changes temporarily
git stash

# Apply stashed changes
git stash apply

# Remove stashed changes
git stash drop

# List all stashed changes
git stash list