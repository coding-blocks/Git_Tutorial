### git config
Usage: git config –global user.name “[name]”  
Usage: git config –global user.email “[email address]”  
-This command sets the author name and email address respectively to be used with your commits.

### git init
Usage: git init [repository name]
-This command is used to start a new repository.

### git clone
Usage: git clone [url]<br/>
-This command is used to obtain a repository from an existing URL.

### git add
Usage: git add [file]  
-This command adds a file to the staging area.

### git commit
Usage: git commit -m “[ Type in the commit message]”  <br/>
-This command records or snapshots the file permanently in the version history.<br/>
Usage: git commit -a  <br/>
-This command commits any files you’ve added with the git add command and also commits any files you’ve changed since then.<br/>
### git diff
Usage: git diff  <br/>
-This command shows the file differences which are not yet staged.<br/>
Usage: git diff –staged <br/>
-This command shows the differences between the files in the staging area and the latest version present.<br/>
Usage: git diff [first branch] [second branch]  <br/>
-This command shows the differences between the two branches mentioned.<br/>

### git reset
Usage: git reset [file]  <br/>
-This command unstages the file, but it preserves the file contents.<br/>
Usage: git reset [commit]  <br/>
-This command undoes all the commits after the specified commit and preserves the changes locally.<br/>
Usage: git reset –hard [commit]  <br/>
-This command discards all history and goes back to the specified commit.<br/>

### git status
Usage: git status  
-This command lists all the files that have to be committed.

### git rm
Usage: git rm [file]  
-This command deletes the file from your working directory and stages the deletion.

### git log
Usage: git log  <br/>
-This command is used to list the version history for the current branch.<br/>
Usage: git log –follow[file]  <br/>
-This command lists version history for a file, including the renaming of files also.<br/>

### git show
Usage: git show [commit]  
-This command shows the metadata and content changes of the specified commit.

### git tag
Usage: git tag [commitID]  
-This command is used to give tags to the specified commit.


### git branch
Usage: git branch  <br/>
-This command lists all the local branches in the current repository.<br/>
Usage: git branch [branch name]  <br/>
-This command creates a new branch.<br/>
Usage: git branch -d [branch name]  <br/>
-This command deletes the feature branch.<br/>

### git checkout
Usage: git checkout [branch name]  <br/>
-This command is used to switch from one branch to another.<br/>
Usage: git checkout -b [branch name]  <br/>
-This command creates a new branch and also switches to it.<br/>

### git merge
Usage: git merge [branch name]  <br/>
-This command merges the specified branch’s history into the current branch.

### git remote
Usage: git remote add [variable name] [Remote Server Link]  
-This command is used to connect your local repository to the remote server.

### git push
Usage: git push [variable name] master  <br/>
-This command sends the committed changes of master branch to your remote repository.<br/>
Usage: git push [variable name] [branch]  <br/>
-This command sends the branch commits to your remote repository.<br/>
Usage: git push –all [variable name]  <br/>
-This command pushes all branches to your remote repository.<br/>
Usage: git push [variable name] :[branch name]  <br/>
-This command deletes a branch on your remote repository.<br/>

### git pull
Usage: git pull [Repository Link]  
-This command fetches and merges changes on the remote server to your working directory.

### git stash
 Usage: git stash save<br/>
-This command temporarily stores all the modified tracked files.<br/>
 Usage: git stash pop  <br/>
-This command restores the most recently stashed files.<br/>
 Usage: git stash list  <br/>
-This command lists all stashed changesets.<br/>
 Usage: git stash drop  <br/>
-This command discards the most recently stashed changeset.<br/>

