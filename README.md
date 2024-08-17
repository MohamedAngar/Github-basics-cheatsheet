### GitHub Basics Cheat Sheet

1. **Setup & Configuration**: 
   - Configure your username with `git config --global user.name "Your Name"` and your email with `git config --global user.email "you@example.com"`. 
   - Check your configuration with `git config --list`.

2. **Repository Management**: 
   - Create a new repository with `git init`. 
   - Clone a repository with `git clone https://github.com/user/repo.git`.

3. **Basic Commands**: 
   - Check the repository status with `git status`. 
   - Add files to the staging area with `git add <filename>` (or add all files with `git add .`). 
   - Commit changes with `git commit -m "Commit message"`. 
   - Push changes to a remote repository with `git push origin main`. 
   - Pull the latest changes from the remote repository with `git pull origin main`.

4. **Branching**: 
   - Create a new branch with `git branch <branch-name>`. 
   - Switch to a branch with `git checkout <branch-name>`. 
   - Create and switch to a new branch with `git checkout -b <branch-name>`. 
   - Merge a branch into the current branch with `git merge <branch-name>`.

5. **Remote Repositories**: 
   - Add a remote repository with `git remote add origin https://github.com/user/repo.git`. 
   - View remote URLs with `git remote -v`. 
   - Change the remote URL with `git remote set-url origin https://github.com/new/repo.git`.

6. **Inspecting & Undoing**: 
   - View commit history with `git log`. 
   - Show changes made (not staged) with `git diff`. 
   - Undo changes in a file and restore it from the last commit with `git checkout -- <filename>`. 
   - Unstage a file with `git reset <filename>`. 
   - Amend the last commit with `git commit --amend -m "New message"`.

7. **Tags**: 
   - Create a tag with `git tag <tag-name>`. 
   - Push a tag to the remote repository with `git push origin <tag-name>`. 
   - List all tags with `git tag`.

8. **Collaboration**: 
   - Fork a repository using the "Fork" button on GitHub. 
   - Create a pull request using the "New Pull Request" button on GitHub after pushing your changes.

9. **Stashing**: 
   - Stash changes with `git stash`. 
   - Apply stashed changes with `git stash apply`. 
   - List all stashes with `git stash list`.

10. **Resetting**: 
    - Perform a soft reset (keeping changes in the working directory) with `git reset --soft HEAD~1`. 
    - Perform a hard reset (discarding changes) with `git reset --hard HEAD~1`.

This cheat sheet covers the basics of GitHub commands for everyday use.
