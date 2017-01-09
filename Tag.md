## Tag commmands

Delete all local tags and get the list of remote tags:

`git tag -l | xargs git tag -d`
`git fetch`
Remove all remote tags

`git tag -l | xargs -n 1 git push --delete origin`
Clean up local tags

`git tag -l | xargs git tag -d`
