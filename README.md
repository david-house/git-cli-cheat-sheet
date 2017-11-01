# git-cli-cheat-sheet
Git command line shortcuts

### Get a list of all the commits with full SHA1, ISO date, and author email
`git log --pretty=format:'%H %aI %ae'`

### Get the last 1 commit with full SHA1, ISO date, and author email
`git log -n 1 --pretty=format:'%H %aI %ae'`

### Get the last 1 commit for a particular file
`git log -n 1 --pretty=format:'%H %aI %ae' -- "file_name_here"`

### Show the remote repository URL
`git remote show origin`

### Add a second remote directory for push
`git remote set-url --add origin FULL_URL_HERE`

### List all the remote repositories
`git remote -v`

