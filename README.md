#creating a new branch and successfully merging changes

##checkout what branches exist in the repo and which one you are on
` git branch `

##create a new branch
` git checkout -b test-branch `

##confirm that you are on the test-branch
` git branch `

##check status of comitted or uncomitted files
` git status `

##add everything in directory you are in
` git add . `

##commit changes
`git commit -m "Add current changes"`

##push changes to branch in remote repo
` git push origin test-branch `

Then submit pull request on GitHub.

##once PR is approved on GitHub
` git checkout master `

` git pull origin master `

` git checkout test-branch `

` git merge master `

##something went wrong?
[oh, shit, git!](http://ohshitgit.com/)