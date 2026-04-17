# Terminal Log

git init
git add .
git commit -m "Initial commit"

git add .
git commit -m "Added project files"

git checkout -b feature-branch
git commit -m "Worked on feature branch"
git checkout main
git merge feature-branch
