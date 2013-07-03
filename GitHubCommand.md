GitHub Basic Commands
====

### For Markdown file [.md] style, see [this page](http://support.iawriter.com/help/kb/general-questions/markdown-syntax-reference-guide)

## Add/modify a file

### Step 1: in the right directory on your local computer, create your file in a terminal.

### Step 2: go to the right directory, commit the file

`ggit add [file name]`
`ggit commit -m [comments]`

### Step 3: Push the commit

#### creates a remote with customized name pointing at the GitHub repository

`ggit remote add [remote name] https://github.com/[username]/[reponsitory name].git`

#### send the commits in the [branch] to GitHub

`ggit push [remote name] [branch]

## Delete a file

### Step 1: Open a terminal, go to the right directory 

`ggit rm [file name and extension]`

### Step 2: Commite the change

`ggit commit -m "[comments]"`

### Step 3: Push the commit

`ggit push [remote name] [branch]`

## Work on other`gs repository: Folk a repo

### Step 1: Fork the other`gs repository on GitHub.com 

* go to the repository`gs GitHub link, [For example](https://github.com/MathCraft/shifrin-mathematica-book)
* click the Fork button on top right corner
* it will appear on your repository page, and there will be [a HTTP Clone link](https://github.com/mathcraftdlou/shifrin-mathematica-book)

### Step 2: Clone it to local computer. Go to the root GitHub directory on your computer, and

`ggit clone [HTTP clone link]`

### Step 3: Confiture remotes

* change directory: 
`gcd [other`s repository folder name]`

* assign the repository to a new remote name:
`ggit remote add [new remote name] [the other`s repository GitHub link, such as 
 http://github.com/MathCraft/shifrin-mathematica-book.git]`g

* Pulls in changes not present in local repository:
`ggit fetch [new remote name]`

## Remotes management

### View existing remotes
`ggit remote -v`

### Renaming a remote
`ggit remote rename [old remote name] [new remote name]

### Removing a remote
`ggit remote rm [remote name]`



 
