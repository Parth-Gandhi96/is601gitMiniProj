## Git Terminology 
- Repository:
Contains all project files and the revision history for every file. A repository can be owned individually or can be used in collaboration with other people in an organization and can be public or private.

- Clone:
A command that is used to make a copy of an existing repository, including all files, branches, and commits to your local computer. By cloning the user is permitted to edit files and can use Git to monitor all changes without having to be online. 
 
- Fork:
A copy of another users repository that allows an induvial to make changes that do not affect the original project.
 
- Branch:
An independent line of development which allows users to continue making modification without affecting the original repository. Once all modifications are made the user can merge the branch into the master branch to publish the changes made. 

- Commit:
Is a record of any revisions to a file or set of files.  Each commit is assigned a hash that helps in identifying the specific changes, when they changes were made, and who created the changes. 

- Merge:
A command that allows a user to take the independent lines of development (branch(s)) in the same repository or from a fork and integrate them into another single branch.

- Checkout:
The act of navigating between branches or previous commits. 

- Push:
A Command that is used to send recent commits from your local repository to a remote repository.

- Pull:
A command that is used to download changes from a remote repository to update a user’s local repository to match that content. For example, if a user makes changes to the remote repository that you are collaborating on, you can pull in those changes to your local file so that it is up to date.  

- Remote:
A common repository that all team members use make modifications., remote repositories are stored on a code hosting service like GitHub. 

- Remote Add:
Creates a new connection record to a remote repository.

- Remote Remove: 
Disconnects a remote from a local repository. 

- Remote Show: 
A command that allows a user to see which remotes are currently connected as well as allowing the user to add new connections or remove existing ones. 

- Status:
A command used to check the current state of the repository. The command also displays modification in your local files that have not been committed to the repository and lets the user see which branch is active and if there are any commits that are not synced to its remote counterpart. 

- Master Branch:
A default branch that points to the last commit that is made by a user. Every time a user commit’s the master branch pointer automatically moves forward. 



## Git basic Commands:

**Getting & Creating Repositories**

 | Command   | Description   |
 | ----------| --------------|
 | ```git init```  | Initialize a local Git repo |
 | ```git clone ssh://git@github.com/[username]/[repository-name].git```   | Create a local copy of a remote repositorysitory |



**Status, File Adding, and Commit**
|Command	|Description|
| ----------| --------------|
|```git status```	| Checks status|
|```git add [file-name.txt]```	| Add a file to the staging area|
|```git add -A```	| Add all new and changed files to the staging area|
|```git commit -m "[commit message]"```	| Commit changes|



**Branching & Merging**
|Command | Description|
|------------ | -----------|
|```git branch``` |	List branches (the asterisk denotes the current branch)|
|```git branch -a```	| List all branches (local and remote)|
|```git branch [branch name]```	| Create a new branch|
|```git branch -d [branch name]``` |	Delete a branch|
|```git push origin --delete [branch name]``` |	Delete a remote branch|
|```git checkout -b [branch name]```	| Create a new branch and switch to it|
|```git checkout -b [branch name] origin/[branch name]```	| Clone a remote branch and switch to it|
|```git checkout [branch name]```	| Switch to a branch|
|```git merge [branch name]``` |	Merge a branch into the active branch|
|```git merge [source branch] [target branch]```	| Merge a branch into a target branch



**Pushing & Pulling**
|Command|Description|
|------------ | -----------|
|```git push origin [branch name]```	|Push a branch to your remote repository|
|```git push -u origin [branch name]```	|Push changes to remote repository (and remember the branch)|
|```git push```	|Push changes to remote repository (remembered branch)|
|```git push origin --delete [branch name]```	|Delete a remote branch|
|```git pull```	|Update local repository to the newest commit|
|```git pull origin [branch name]```	|Pull changes from remote repository|
|```git remote add origin ssh://git@github.com/[username]/[repository-name].git```|Add a remote repository|
|```git remote set-url origin ssh://git@github.com/[username]/[repository-name].git```	|Set a repository's origin branch to SSH|

![Git symbol](images/Giticon.png)
 
