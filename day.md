# One day in Fremont
### Ate breakfast in McDonald`s
* I ate __fired chicken__ and **french fries** for breakfast.
### We sang songs in *chinese KTV*
- That was very funny!
### We ate lunch in **Little Taipei**
- we ate:
1. **Sweet sour Chinese noodles**
2. **fish fillet with pickled vegetable soup**
3. __Boiled beef__
- Awesome food! I like that restaurant! I will come back again!
### Ate dinner in *Korean BBQ*
- Not as good as that Chinese restaurant, but still OK.
### At the end of that day, we ate dessert in a shop from *Hong Kong*.
* Good tasted! I never had that in Fresno.
### Finally, I hope I lived in Fremont!!!
#About Git
## Git is currently the world's most advanced distributed version control system !
## Normally, git would ask you about your email address and user name,use command "git config --global user.name" and "git config --global user.email" to input the name and email.
## use command "git init" to active a directory to be a repository, that way the stuff in this directory can be managed by git.
## use command "git commit -m" to add information when adding new things to repository.
## use command "git status" to see what change has been made.
## if "git status" tells you there are some change has been made, you can use "git diff" to see what has been changed
## use command "git log" to see all of the logs in repository.
## use command" git pull " to pull the newest files to your local repository.
## use command " git push" to push the newest files to the remote repository from local repository.
## use command "git branch" to add a new branch for your git workflow.
## use command "git checkout" to switch to a new branch from the brand you currently at.
## use command "git merge" move the head to the specify branch.
## use command "git rebase" to combine two branch into one branch. but the original branch which was moved was still there.
# About git branch:
 ## Git strings them together into a timeline, which is a branch. Up to now, there is only one time line. In Git, this branch is called the main branch, that is, the master branch. HEAD strictly does not point to commit, but to master, master is to commit, so HEAD points to the current branch. At the beginning, the master branch is a line, Git points to the latest submission with the master, and then points to the master with the HEAD, to determine the current branch and the submission point of the current branch. With each commit, the master branch moves one step forward, so that as you commit, the line of the master branch is getting longer and longer.
# Command about branch:
## Git encourages extensive use of branches:
## View branches: git branch
## Create branches: git branch <name>
## Switch branches: git checkout <name>
## Create + switch branch: git checkout -b <name>
## Merge a branch to the current branch: git merge <name>
## Delete branches: git branch -d <name>
## use command "git origin push branchname:branchname" to push local branch to remote branch.