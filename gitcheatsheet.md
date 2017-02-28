
$git init [repository-name]
	Creates a new repository with specified name

$git clone [url]
	Clones an existing repository and its history

$git status
	Lists all new or modified files that haven't been commited

$git add [file]
	Updates the index and holds a 'snapshot' that is taken as the contents of the next commit (AKA staging)

$git reset
	unstage a file while retaining the changes in working directory	

$git commit -m "[descriptive message]"
	Records file 'snapshots' into version history

$git push	
	Updates remote repositories using local repositories 

$git branch
	Lists all of the local branches in the current repository

$git branch	[branch-name]
	Creates a new branch

git checkout [branch-name]
	Switches to the specified branch and updates the working directory

git merge [branch]
	Combines the specified branch's history into the current branch	

git branch -d [branch-name]
	Deletes the specified branch	

$git log
	Shows all commits in the current branches history	

$git request-pull [-p] <start> <url>[<end>]
	Generates a request asking your upstream project to pull changes into their tree

