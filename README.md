##create a new branch

` git checkout -b test-branch `

##check status of comitted or uncomitted files
` git status `

##add everything in directory you are in
` git add . `

##commit changes
`git commit -m "Add current message"

##push changes to branch in remote repo
` git push origin test-branch `

Then submit pull request on GitHub.

##Once PR is approved on GitHub
` git checkout master `

` git pull origin master `

` git checkout test-branch `

` git merge master `

##Something went wrong?
[Oh, shit, git!](http://ohshitgit.com/)