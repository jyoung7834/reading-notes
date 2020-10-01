# Git
Snapshots

Git is a DVCS that stores data in a file system made up of snapshots. Each time you save a changed version of your project — called commit — Git creates a snapshot of the file and stores a reference to it. If the file has not changed, Git only stores a reference to the already-stored identical version of it.

Local Operations

Git mostly relies on local operations because most necessary information can be found in local resources. This allows for process expediency because a project’s history resides on the local disk, eliminating the need to fetch history information from the server, and allowing one to continue work on a project even when not online or on a VPN.

Tracking Changes

Every single change applied to any file or directory is tracked by Git. And, as the gatekeeper, Git will always detect file corruption or loss of information in transit.

Loss of Data

Git is set up to greatly minimize the possibility of irreversible damage to files, such as accidentally lost data. Git makes it extremely difficult for a snapshot of your file that is committed to be lost.

States

Files in Git can reside in three main states: committed, modified and staged.

Committed

Data is securely stored in a local database

Modified

File has been changed but not committed to the database
Package Manager

You can try installing Git via your distribution’s inherent package management tool. 
$ sudo apt-get install git

 ## Remember these (GIT Notes)
- mkdr = make directory
- ls = list
- mkdr 102 201 301 401 enter
- cd 102
- pwd
- git clone add hyperlink from github.com
- cd apples
- ls -a
- code .
- git status
- git add then add file in red
- git add "README.md"
- git commit -m "reason or name"
- git push origin master
- make sure you spell correctly
- Make sure you have your github user and pw
- cd ..