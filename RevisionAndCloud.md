## Revisions and the Cloud


Git is a version control tool used widely by developers across the world. 
It helps individual developers keep track of changes as they work on different features in the same project, and helps teams organize their code. 
Git works by recording the changes you make to a project, storing those changes, then allowing you to reference them as needed. 
As our instructor previously stated, "If git was a sport, github would be the area." 
To me, git is a language that makes changes to your git repository. 

  
  *"Git is a DVCS that stores data in a file system made up of snapshots. Each time you save a changed version of your project —*
  *called commit — Git creates a snapshot of the file and stores a reference to it.*
  *If the file has not changed, Git only stores a reference to the already-stored identical version of it."*
  
  A Git project can be thought of as having three parts:

- A Working Directory: where you’ll be doing all the work: creating, editing, deleting and organizing files
- A Staging Area: where you’ll list changes you make to the working directory
- A Repository: where Git permanently stores those changes as different versions of the project

*The Git workflow consists of editing files in the working directory, adding files to the staging area, and saving changes to a Git repository. *
*In Git, we save changes with a commit, which we will learn more about in this lesson.*

Some git keywords:

> git add: Stages your changes & gets them ready for its snapshot.

> git commit: Saves the changes (A new version) Takes a snapshot.

> git push: Pushes through the changes to github. Sends the snapshot to the cloud/remote

> git pull: Pulls all changes from github/cloud/remote.

 

*By running the git remote command, you can view the short names, such as “origin,” of all specified remote handles.*

*By using git remote -v, you can view all the remote URLs next to their corresponding short names.*
