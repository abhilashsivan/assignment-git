#Basic git commands
configuring git account

$ git config --global user.email "Your email" #global specifies the current user

$ git config --global user.name "Your username"

cloning a remote repository into local

$ git clone "the url of repository to be cloned"

initializing an existing folder as git folder

$ git init #inside the folder will create a .git file which makes the folder a git repository.

commit a change

$ git add . # adds everything changed from local to staging

$ git commit -m "commit message" # commits everything in staging to be ready to be pushed to Github

push to online repo

$ git remote add origin "Link of the remote repo" #adds a reference to the remote repo to track changes(when push and pull)

$ git push origin master #origin is the repo we're pushing intoa dn master is the branch

#Branch commands
creating a new branch

$ git branch # list all branches in working folder

$ git branch newBranchName

$ git checkout newBranchName # switch to branch newBranchName

$ git push origin newBranchName

merging new branch to old branch

$ git checkout oldBranchName

$ git merge branchName

$ git push origin oldBranchName

$ git branch -D branchName # deletes local branch branchName

$ git push remoteName --delete branchName # deletes remote branch branchName
