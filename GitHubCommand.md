GitHub Basic Commands
====

### For Markdown file [.md] style, see [this page](http://support.iawriter.com/help/kb/general-questions/markdown-syntax-reference-guide)

## Add/modify a file

### Step 1: in the right directory on your local computer, create your file in a terminal.

### Step 2: go to the right directory, commit the file

'git add [file name]'
'git commit -m [comments]'

### Step 3: Push the commit

#### creates a remote with customized name pointing at the GitHub repository

'git remote add [remote name] https://github.com/[username]/[reponsitory name].git'

#### send the commits in the [branch] to GitHub

'git push [remote name] [branch]

## Delete a file

### Step 1: Open a terminal, go to the right directory 

'git rm [file name and extension]'

### Step 2: Commite the change

'git commit -m "[comments]"'

### Step 3: Push the commit

'git push [remote name] [branch]'



