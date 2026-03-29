Terminal.md 

## Step 1: Create project folder
mkdir cli-git-project
cd cli-git-project

## Step 2: Initialize git
git init

## Step 3: Create README
touch README.md

## Step 4: Check status
git status

## Step 5: Add README
git add README.md

## Step 6: First commit
git commit -m "Initial commit: add README"

## Step 7: Create app file
touch app.js

## Step 8: Add content
echo "console.log('Hello World');" > app.js

## Step 9: Stage and commit
git add app.js
git commit -m "Add app.js with basic code"

## Step 10: Create .gitignore
touch .gitignore

## Step 11: Add ignore rules
echo "node_modules/" >> .gitignore
echo ".env" >> .gitignore

## Step 12: Commit .gitignore
git add .gitignore
git commit -m "Add .gitignore file"

## Step 13: Create branch
git checkout -b feature-update

## Step 14: Edit app.js
echo "// new feature" >> app.js

## Step 15: Commit changes
git add app.js
git commit -m "Update app.js in feature branch"

## Step 16: Switch back to main
git checkout main

## Step 17: Merge branch
git merge feature-update

## Step 18: Push to GitHub
git remote add origin https://github.com/your-username/cli-git-project.git
git push -u origin main

Gitignore
node_modules/
.env
*.log
.DS_Store
.vscode

README.md
# CLI & Git Workflow Project

## 📌 About
This project shows my understanding of using the command line and Git for version control.

## 🚀 What I Did
- Initialized a Git repository
- Created and tracked files
- Made multiple commits
- Created a branch and merged it
- Connected project to GitHub

## 🛠 Tools Used
- Git
- Terminal (CLI)
- GitHub

## 📂 Files
- README.md
- app.js
- .gitignore
- terminal-log.md

## 🔧 How to Run
Clone the repo:
git clone https://github.com/your-username/cli-git-project.git

Go into folder:
cd cli-git-project

Run file:
node app.js

## 🌿 Git Process
- git init
- git add
- git commit
- git checkout -b feature-update
- git merge

## 📊 Commit History
1. Initial commit: add README  
2. Add app.js with basic code  
3. Add .gitignore file  
4. Update app.js in feature branch  
5. Merge feature-update branch  

## 👤 Author
Your Name
