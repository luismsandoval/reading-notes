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

### Downloading Git

### **Mac OS X**

- Terminal: Run Git from the Terminal, if not installed, you will be prompted.
- Git Website: [Download](http://git-scm.com/download/mac)
- GitHub: [Download](http://mac.github.com)

### **Windows**

- Git Website: [Download](http://git-scm.com/download/win)
- GitHub: [Download](http://windows.github.com)

### **Linux**

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

### Graphical Clients 

There are plenty of Graphical User Interface(GUI) tools. [Here](https://git-scm.com/downloads/guis) are some GUI clients to try out.

### Initial Customization 

Before we use Git, first we need to perform some changes. You will only need to do this **once** on any machine, however if you do need to change some settings, repeat the following steps.

#### *Configuration of Variables*

Use thie following command to configure settings in Git.

```
git config
```

#### *Identity Setting*

After installing Git, users first need to set up their username and email address.

Use the following command:

```
git config --global user.name "My Name"

git config --global user.email "myemail@email.com"
```

Use the following command to confirm your settings are correct:

```
git config --global user.name (should return My Name)

git config --global user.email (should return myemail@email.com)
```
*global applies these settings to anything on the system.

### Check Settings

```
git config --list
```

### Getting Help

Try these commands to access the manual for further help.

```
git help command

git command --help

man git-command
```

## Now that Git is ready, let's set up our Git Repository

### Importing

Follow these steps:

1. Switch to the project's directory.
2. Use the git init command to creat a new git repository.

```
$ git init
```

3. To track these repositories, perform an initial commit by using the following commands:

```
$ git add *.c

$ git add LICENSE

$ git commit -m "any notes here"
```

### Cloning

To create a copy of an *existing* Git Repository from a server like GitHub, use the following command in the project directory:

```
$ git clone https://github.com/mycoolgitpage
```

This clone copies all files for a project into a new directory called "mycoolgitpage"

## Workflow

