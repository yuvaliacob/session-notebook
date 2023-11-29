// A list of git commands and tips

GitHub and Markdown Tips
https://github.com/spiced-academy/coriander-web-dev/blob/main/sessions/github-and-markdown/github-and-markdown.md

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

// to remove connected repository
git remote remove origin

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

// Good commit messages

- Be short and descriptive
- Always use english
- The first word should be a verb: "add", "fix", "remove", etc.
- Use imperative and present tense: "add shop page" instead of "added shop page"
- Do not end your commit message with a period
- When in doubt, describe why you did something instead of how: "fix typo" instead of "replaced the letter a with an e in the second word"
