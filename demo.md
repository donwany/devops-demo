gh repo create devops-demo -d "devops" --public

git "#devops" >> README.md
git init
git add .
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/donwany/devops-demo.git
git push -u origin main

# create a new branch
git branch <new-branch-name>

# switch branch
git checkout -b <new-branch-name> <existing-branch>
git checkout -b <new-branch-name>
git checkout <branch-name>

# commit to new branch
git push -u origin <new-branch-name>

# merge branch
git merge <new-branch-name>

# delete a branch
git branch -d <branch-name>
