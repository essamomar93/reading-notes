# Git 

### what is the git?
Git is a VCS that stores data in a file system made up of snapshots.
  
### The local Git repository has three components:
1. Working Directory: The actual files reside here. 
2. Index: The area used for staging. 
3. Head: Points to the most recent commit. 


### The Life Cycle of File Status

1. After you edit a file, Git flags it as modified because of changes made after the previous commit.
2. You stage the modified file 
3. Then, you commit staged changes 

#### Track one file only by using the following format:
$ git add filename

#### After staging one or multiple files, you should commit the changes and record what you did within the commit message:
$ git commit -m “made change x,y,z”

#### Next, you would push changes to a remote repository. We will discuss remote repositories in more depth in the next section. For now, we will look at a general overview of pushing changes to remotes.
$ git push origin master

