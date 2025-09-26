# Python DevOps Project - Git Workflow

This repository demonstrates a simple end-to-end DevOps workflow using Git and GitHub. The sample code is a basic Python script.

## Prerequisites

- Git installed on Ubuntu
- A GitHub account

## Commands Used

  ### 1. Initialize Local Repository
      
      ```
      git init
      ```
      Initialize a new Git repo in the current directory.
      
  ### 2. Add Files
      
      ```
      git add .
      ```
      Add specific files or all changes to the staging area.
      
  ### 3. Commit Changes
      
      ```
      git commit -m "Your commit message"
      ```
      Commit staged changes to the local repository with a message.
      
  ### 4. Set Up Remote Repository
      
      ```
      git remote add origin https://github.com/ShaikAbbas2092/Day-4-Version-control-in-Git.git
      ```
      Connect the local repo to a remote GitHub repository.
      
   ### 5. Rename Branch to Main
      
      ```
      git branch -M main
      ```
      Rename the current branch to `main` as the primary branch.
      
   ### 6. Push Changes to Remote
      
      ```
      git push -u origin main
      ```
      Push local commits to the remote repository's main branch.
      
   ### 7. Create and Switch Branch
      
      ```
      git checkout -b dev
      git checkout -b feature/26-9-2025
      ```
      Create and switch to a new branch.
      
  ### 8. Push New Branch to Remote
      
      ```
      git push -u origin dev
      git push -u origin feature/26-9-2025
      ```
      Push the newly created branch to GitHub.
      
  ### 9. Pull Latest from Remote
      
      ```
      git pull origin main
      ```
      Sync local branch with the remote repository to fetch changes.
      
  ### 10. Tag a Release Version
      
      ```
      git tag -a v1.0.0 -m "release message"
      git push origin v1.0.0
      ```
      Create and push a tag for release versioning.
      '''

