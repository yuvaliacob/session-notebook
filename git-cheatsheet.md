// A list of git commands

// To turn a folder into a git repository
git init

git clone <SSH repository address>

git remote -v

git status

// . mean all files
git add .

// to do a commit
git commit -m "<comment>"

// commit from branch to main = merge
git push origin main

// see past changes
git log

// to change the connected remote repository
git remote set-url origin <repository URL>

git pull

// create new git branch
git switch -c "<NAME>"

//to go back to the main branch
git switch main

// go back to previous branch
git switch -

// push to specific branch
git push origin <NAME of BRANCH>

- pull request on GitHub in order to merge branch back to main

- delete branch after merging back to main

- back on local git in order to update after merging: git pull

// shows branch/commit history
git log --graph
