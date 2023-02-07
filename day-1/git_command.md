git add => add file to staging area
to use git add, `git add <file_name>`

to unstage => git rm --cached <file>

git status => show status of working directory and staging area

git commit => commit changes to local repo


<!-- process to create a new repository in github and push your code to it -->
to point our local repository to github =>
`git remote add origin https://github.com/silverchill/onramp-cont.git`

initialize our current base branch to main `git branch -M main`

git push -u origin main

git push => push changes to remote repo
to use the command, `git push <remote_name> <branch_name>`

<!-- whenever you make changes to your project, follow this process to push to github-->
`git add .`
`git commit -m 'your commit message'`
`git push`
