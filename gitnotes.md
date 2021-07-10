# Git Notes [git notes link](https://blog.udemy.com/git-tutorial-a-comprehensive-guide/)
 
 **Version Control** is a system that allows you to revisit various versions of a file or set of files by recording changes.
 By using a Version Control System (VCS), mistakes with files can easily be rectified.
 
 **Centralized Version Control** This system entails a single server storing all changes and file versions, which can be accessed by various clients.
 
 **Distributed Version Control**  addresses the major vulnerability of the CVS: the server as a single point of failure.a DVCS allows clients to create mirrored repositories.
 If a CVS goes down, collaborators cannot work with each other on a file or save changes and new versions.
 
 **What is Git?**
 Git is a DVCS that stores data in a file system made up of snapshots.
 Each time you save a changed version of your project called commit. Git creates a *snapshot* of the file and stores a reference to it.
 
 **Files in Git can reside in three main states:*
 -committed Data is securely stored in a local database
 -modified  File has been changed but not committed to the database
 -staged Flagged a file’s changed version to be committed in the next snapshot
 
 **Setting up a Git Repository**
 To import an existing project or directory into Git
 -$ cd test (cd = change directory)
 -$ git init
 
 **Tracking Repository 
- $ git add *.c
- $ git add LICENSE
- $ git commit -m “any message here”

**Cloning**
 You can create a copy of an existing Git repository from a particular server by using the clone command with a repository’s URL:
 - $ git clone [[(https://github.com/test]]

**To clone a repository into a directory with another name (of your choosing) use this command format**
-[[$ git clone https://github.com/test mydirectory]] *(The command above makes a copy of the target repository in a directory named “mydirectory.”)*

 **Seeing your Repositories**
 
By using git remote -v, you can view all the remote URLs next to their corresponding short names.

$ cd example

$ git remote -v

remote1 https://github.com/remote1/example (fetch)

remote1 https://github.com/remote1/example (push)See Latest Commits


life is beautiful :) ( my changes)
