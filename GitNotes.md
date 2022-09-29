# Git Notes from Reading

## What is Git

Git is a *Distributed Version Control System* (DVCS) that stores data in a file system made up of snapshots. Each time you save a changed version of your project — called commit — Git creates a snapshot of the file and stores a reference to it. Git mostly relies on local operations because most necessary information can be found in local resources. Thus eliminating the need to fetch history information from the server, and allowing one to continue work on a project even when not online or on a VPN. Every single change applied to any file or directory is tracked by Git.

Git traces its roots to the open source software project Linux kernel. Linus Torvalds began creating Git with the intention of creating a DVCS with a workflow design similar to that of BitKeeper, which was also fast, Git allowed for non-linear development via multiple branches, could support large projects, possessed strong mechanisms preventing corruption, and had a simple design. Since its inception in 2005, Git has become one of the most utilized Version Control Systems in the world.

## Git Commands

~~~bash
git status
~~~

Shows which branch you are in and the state of files.  

~~~bash
git add (filename)

git add*
~~~

Allows the user to track files and stage them for commiting.

~~~bash
git commit -m 'change made'
~~~

Commits a snapshot of all changes to tracked files in the working directory.

~~~bash
git push origin main
~~~

Pushes changes from local repo to remote repo names origin.

[Back Home](/README.md)

### Other Resources

[Letter to a Friend](/SummeryForAFriend.md)

[Notes on Text Editor](/TextEditorCommand.md)

[Notes on Wireframs and HTML](/WireframeHTML.md)

[Notes on CSS](/CSSnotes.md)

[Notes on Java Script](/js1.md)

[Notes on Functions](/NotesOnFunctions.md)

[Notes on Operators and Loops](/OperatorsLoops.md)
