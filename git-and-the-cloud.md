# Git and the Cloud

## Before we jump in to Git, we must first understand *Version Control*
There are a few types of version control we will go over, but they all essentially do the same thing; allow you to revisit multiple versions of a file by recording changes. This makes it easy to rectify mistakes. Yay!

**Local Version Control(VCS):** One database on your harddrive saving all changes.

**Centralized Version Control(CVCS):** A single server storing all changes to allow for collaborative work.

**Distributed Version Control(DVCS):** Allows for multiple *mirrored* repositories or data backups. This allows teams to collaborate with each other simultaneously.

## What's Git?
Git is a *DVCS*! Let's go over some basic features.
- **Snapshots:** Every time you save a changed version of code (***commit***), Git takes a "snapshot" and stores your file.
- **Local Operations:** Since Git relies mostly on local operations, this allows you continue work even when offline! No excuses not to work now. :grimacing: 
- **Tracking Changes:** Git will track any and all changes for you, they are the *almighty gatekeeper*. Because of this, Gut will **always** detect a file corruption.
- **Loss of Data:** *Not happening*
- **States:**
  - Committed: Data securely stored in a local database.
  - Modified: File changed but **not** committed.
  - Staged: Flagged to be committed in the next *snapshot*.

## Let's *Git it*!

### Mac OS X

- Terminal: Run Git from the Terminal, if not installed, you will be prompted.
- Git Website: [Download](http://git-scm.com/download/mac)
- GitHub: [Download](http://mac.github.com)

### Windows

- Git Website: [Download](http://git-scm.com/download/win)
- GitHub: [Download](http://windows.github.com)

### Linux

- Package Manager:
  - For Fedora: 
  ```
  $ sudo yum install git
  ```
  - For Ubuntu: 
  ```
  $ sudo apt-get install git
  ```
- Git Website: [Download](http://git-scm.com/download/linux)
