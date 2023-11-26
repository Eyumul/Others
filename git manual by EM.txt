first of all configer your name and email so others can know that you made changes when you do.
$ git config --global user.name "Your name"
$ git config --global user.email Yourmail@example.com
create a master branch
$ git config --global init.default branch main
create a repositary( when you run the below code in a terminal the directory inwhich you are in will be the repositary) 
$ git init
you can check your status everytime using
$ git status
and you can see the changes that aren't commited
$ git diff
you can track files and repositaries by using
$ git add file_name
commit your tracked files ( save a change made to tracked files and cearte a copy of pervious ones)
$ git commit -m "your message"
to track then commit a file that is untracked using single line of code use
$ git commit -a -m "your message"
to see the history of the commits
$ git log
to see the history of the commits breifly
$ git log -p
to see the history of each commits in oneline
$ git log --oneline 
to reset a specific change
$ git reset commit_id
to create a branch
$ git branch branch_name
to switch to another branch
$ git switch branch_name
to merge your branch to the master branch ( main branch) use
$ git merge -m "your_message" branch_name
to delete a branch use
$ git branch -d branch_name