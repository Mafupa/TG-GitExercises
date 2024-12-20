# THE GYM Git Exercises Command History


## Bundle 1
### Exercise 1
git init\
vim README.md\
git add .\
git commit -m "Initial File"\
git branch\
git branch -m main master\
git branch\
git branch -m master main\
git branch\
git add .\
git commit -m "Changed branch name to master than back to main"\
git remote add origin https://[token]@github.com/Mafupa/TG-GitExercises.git\
git push -u origin main\
git branch dev\
git checkout dev\
git branch test\
git branch -d test\
 
### Exercise 2
vim home.html\
git add home.html\
git stash
vim about.html\
git add about.html\
git stash\
vim team.html\
git add team.html\
git stash\
git stash pop stash@{1}\
git stash pop stash@{1}\
git commit -m "B1 Ex2 Added about.html and home.html"\
git push -u origin dev\
git stash pop\
git reset\
rm team.html\

## Bundle 2
### Exercise 1
git branch ft/bundle-2\
git checkout ft/bundle-2\
vim services.html\
git add services.html\
git commit -m "B2 Ex1 added services.html"\
git push -u origin ft/bundle-2\

### Exercise 2
git checkout main\
git pull\
git branch ft/service-redesign\
git checkout ft/service-redesign\
vim services.html\
git add services.html\
git commit -m "B2 Ex2 Added changes to services.html"\
git push -u origin ft/service-redesign\
