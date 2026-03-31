# G-LAB-2-CONNECTING-GIT-BASH-TO-GIT-HUB-REPOSITORY

Objective:
To connect a local Git repository to a GitHub repository and push files to GitHub.
Requirements:
Git installed (Git Bash)
GitHub account
Internet connection
Procedure:
Create Project Folder in Git Bash:

mkdir project
cd project
Create Files:

touch file{1..10}
Configure Git Username and Email:

git config --global user.name "your_username"
git config --global user.email "your_email"
Initialize Git Repository:

git init
Add Files to Staging Area:

git add .
Commit Files:

git commit -m "Initial commit"
Create Repository on GitHub:
Go to GitHub
Click on New Repository
Copy the repository URL
Connect Local Repo to GitHub:

git remote add origin <repository_url>
Push Files to GitHub:

git push -u origin master
# Result:
Local repository successfully connected to GitHub and files pushed online.
# Conclusion:
This lab demonstrates how to link a local Git project with GitHub and upload files using Git commands.
