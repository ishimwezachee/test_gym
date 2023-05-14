# Commands used 

### Exercises 1
- git init
- git add README.md
- git commit -m "first commit"
- git branch -M main
- git remote add origin https://github.com/ishimwezachee/Gym-Git-Exercise-Solutions.git
- git push -u origin main
- git checkout -b dev
- git push -u origin dev
- git checkout -b test
- git push -u origin test
- git checkout dev
- git branch -D test
- git push origin --delete test

### Exercises 2

- touch home.html
- git add home.html
- git stash 
- touch about.html
- git add about.html
- git stash
- git touch team.html
- git add team.html
- git stash
- git stash list 
- git stash pop stash@{1}
- git stash pop stash@{1}
- git add --all
- git commit -m'setup home and about page'
- git push origin dev
- git stash pop stash@{0}
- git reset --hard
