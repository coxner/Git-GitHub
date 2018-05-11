# Git-GitHub

In short Git is a version control system that stores different versions of your files. You can think of it as a undo button. If any of your files are ever to break Git provides a reference point you can go back to. 

`git init` initalizes/ creates a new git repository. 

A commit can be refered to as a user created check point. 

To view every commit that has ever been made in a Git we use `git log`. We can also use `git log --stat` which provides more detailed stats on files that have changed with each commit. 

To view the differnce between two versions of files/commits we can use `git diff`. To find the diff between two commits we first call `git log` to obtain the commit ids we then run `git diff commit_id1 commit_id2`. To compare two files we would simply do a `git diff file_1 file _2`.

Copying the history of a git repo from one computer to another is known as cloning.

Head is what git uses to refer to the commit it is currently on.

### The Git Workflow
![Alt](images/gc.png)