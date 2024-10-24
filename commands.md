Git Commands for DevOps
File Operations
touch hello.txt
touch dosto.txt
touch nibba.txt nibbi.txt
rm dosto.txt
rm hello.txt
Git Status and Staging
git status
git add nibba.txt nibbi.txt
git status
Committing Changes
git commit -m "adding nibba nibbi"
touch hello-dosto.txt
git status
git add hello-dosto.txt
git commit -m "adding nibba nibbi"
git status
Removing Files
rm hello-dosto.txt
git status
git add hello-dosto.txt
git commit -m "adding nibba nibbi"
git status
Restoring Files
git restore hello-dosto.txt
git restore --staged hello-dosto.txt
git status
git rm hello-dosto.txt
git status
git commit -m "adding nibba nibbi"
Git Configuration
git config --global user.name "Gagneet_Kaur"
git config --global user.email "gagneetkaur1998@gmail.com"
Branch Management
git checkout -b dev
git add feature1.txt
git commit -m "adding in dev branch"
Switching Branches
git switch master
git add feature2.txt
git commit -m "adding in master branch"
git switch dev
