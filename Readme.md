`git checkout --orphan temp_branch`

`git add .`

`git commit -m 'init'`

`git branch -D master`

`git branch -m master`

`git push -f heroku master`