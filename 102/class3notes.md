# What is GIT

**Snapshot** - Git is a DVCS that stores data in a file system made up of snapshots. Each time you save a changed version of your project — called commit — *Git creates a snapshot of the file and stores a reference to it. If the file has not changed, Git only stores a reference to the already-stored identical version of it.*

**Local Opperations** - *Git mostly relies on local operations because most necessary information can be found in local resources. This allows for process expediency because a project’s history resides on the local disk, eliminating the need to fetch history information from the server, and allowing one to continue work on a project even when not online or on a VPN.*

**Tracking Changes** - *Every single change applied to any file or directory is tracked by Git. And, as the gatekeeper, Git will always detect file corruption or loss of information in transit.*

**Loss of Data** - *Git is set up to greatly minimize the possibility of irreversible damage to files, such as accidentally lost data. Git makes it extremely difficult for a snapshot of your file that is committed to be lost.*

**States** - *Files in Git can reside in three main states: committed, modified and staged.*
**-Committed.** *Data is securely stored in a local database*
**-Modified.** *File has been changed but not committed to the database*

### Local Repository Structure

-Working Directory: The actual files reside here.
-Index: The area used for staging
-Head: Points to the most recent commit

### Saving Changes
**Tracked** - *Tracked files can be modified, unmodified, or staged; they were part of the most recent file snapshot.
**Untracked** - *Untracked files were not in the last snapshot and do not currently reside in the staging area.
After cloning a repository, files have tracked status and are unmodified because they have been checked out but not edited.*

### Tracking and staging a new file.
*Single file* - git add "filename"
*All files* - git add

*Single File* - git commit -m “made change x,y,z”
*All files* - git commit -a

*Pushing change* - git push origin main

**If you are not ready to commit changes *git stash* this command temporarily removes changes and hides them**

### “Seeing Your Remote”.

- *git remote* - Command that lets you view short names, the origin of all sacific remote handles.
- *git remote -v* - you can view all the remote URLs next to their corresponding short names.

