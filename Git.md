# Git
First you need to know more about the **Version Control** is a system that allows you to revisit various versions of a file or set of files by recording changes. Through version control, one can revert a file or project to a previous version, track modifications and modifying individuals, and compare changes. By utilizing a Version Control System (VCS), mistakes with files can easily be rectified.
So **Git** is a DVCS that stores data in a file system made up of snapshots. Each time you save a changed version of your project — called commit — Git creates a snapshot of the file and stores a reference to it. If the file has not changed, Git only stores a reference to the already-stored identical version of it. Also it set up to greatly minimize the possibility of irreversible damage to files, such as accidentally lost data. Git makes it extremely difficult for a snapshot of your file that is committed to be lost.


Files in Git can reside in three main states: committed, modified and staged.
* Committed

Data is securely stored in a local database

* Modified

File has been changed but not committed to the database
* Staged

Flagged a file’s changed version to be committed in the next snapshot

The local Git repository has three components:

  Working Directory: The actual files reside here.
  Index: The area used for staging
  Head: Points to the most recent commit
  All files in a checked out (or working) copy of a project file are either in a tracked or untracked state.

* Tracked
Tracked files can be modified, unmodified, or staged; they were part of the most recent file snapshot.
* Untracked
Untracked files were not in the last snapshot and do not currently reside in the staging area.

And that is an illustration of the git work flow:
$ git status

On branch master

nothing to commit, working directory clean

*This information indicates which branch you’re on (we will cover branches in a later section) and states “working directory clean,” which means that files have tracked or modified status at the moment. Also, no untracked files are present because Git has not listed any.
Committing a File

After staging one or multiple files, you should commit the changes and record what you did within the commit message:

$ git commit -m “made change x,y,z”

*This step has committed changes for the file or files (you can have one commit message for multiple files, if applicable) to the HEAD.
Committing All Changes

$ git commit -a

*This command commits a snapshot of all modifications to tracked files in the working directory.
Pushing Changes

Next, you would push changes to a remote repository. We will discuss remote repositories in more depth in the next section. For now, we will look at a general overview of pushing changes to remotes.

Example:

$ git push origin master

*This command pushes changes from the local “master” branch to the remote repository named “origin”.

*For cloned repositories, Git will automatically give the name “origin” to the server from which you cloned and the name “master” to your local repository. However, these names can be changed by the user.
Stashing Changes

When you are not ready to commit changes but do not want to lose them either, git stash is a great option. This command temporarily removes changes and hides them, giving you a clean working directory. When you are ready to continue working on the changes, simply use the git stash apply command to retrieve the hidden changes.
