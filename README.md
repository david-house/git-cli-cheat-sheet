# git-cli-cheat-sheet
Git command line shortcuts

### Get a list of all the commits with full SHA1, ISO date, and author email
`git log --pretty=format:'%H %aI %ae'`

### Get the last 1 commit with full SHA1, ISO date, and author email
`git log -n 1 --pretty=format:'%H %aI %ae'`

### For a particular file
`git log -n 1 --pretty=format:'%H %aI %ae' -- "file_name_here"
