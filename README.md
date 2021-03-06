# IS601-git-project

## Git Commands 
###### Repository - Container to hold your project and track all of the changes you make.
###### Clone - Git command used to clone or copy an existing repository
###### Fork - Git command which copies a repository, allowing the user to freely experiment and change things, often used to propose changes to someone else's project.
###### Branch - A branch is an independent line of development.
###### Commit - A commit is a revision to a file or set of files.
###### Merge - Combining separate branches into a single unified branch
###### Checkout - Git command used to create a new branch (git checkout -b) or to navigate to an existing branch (git checkout existing-branch) Similar to the cd command but for branches.
###### Push - Git command to upload your local commits(revisions) to a remote repository, the one on github.com for example.
###### Pull - Git command which bring a local repository up to date with a remote repository, one on github.com for example.
###### Remote Add / Remove / Show - Remote add/remove/show adds/removes/shows a remote branch
###### Status - Git status is a way to check which files have been changed while you’re working
###### Master - Name of default branch, contains production ready files.


**Linux Commands**

***Cd***

The Cd command is used to change the current working directory. This is used when you are working with two or more directories and want to toggle between them.

> Vagrant@docker-test:~$ `cd` IS601 

upon this command, we toggle from current directory to IS601 directory.

***mkdir***

The mkdir command is used to create a new directory in whatever directory you are currently in.

> Vagrant@docker-test:~$ `mkdir directory-name`

upon this command, a new directory named as the user mentioned is created.

***cp***

This command is used to copy files or group of files or directory. It creates an exact image of a file on a disk with different file name. cp command require at least two filenames in its arguments.

> Vagrant@docker-test:~$ `cp Source Destination`

> Vagrant@docker-test:~$ `cp Source Directory`

In the above code, the source file is copied to destination or directory.

***pwd***

This linux command which stands for present working directory, basically lets you check which directory you are currently in.

> Vagrant@docker-test:~$ `pwd`

`/home/vagrant/IS601`

upon using this command, it lets us now that we are in the IS601 directory.

***ls***

This command lets you see all of the files and other directories that exist in the directory that you are currently in.

> Vagrant@docker-test:~$ `ls`
`IS601 IS601test`

upon using this command, it lists all the directories and branches.

***mv***

Mv is a command which lets you move files or directories, takes two arguments, the thing you want to move, and its new destination.

> Vagrant@docker-test:~$ `mv [OPTION]... [-T] SOURCE DEST`

> Vagrant@docker-test:~$ `mv [OPTION]... SOURCE... DIRECTORY`

upon this command, the file is moved from the mentioned source to destination.

***rm***

This command is used to remove a file or a directory in linux.

> Vagrant@docker-test:~$ `rm file-name`

upon this command, the file name mentioned is deleted.

***history***

This is command to show the last commands that you have used.

> Vagrant@docker-test:~$ `history`

It lists every code that has been used before.

***Home directory and ~***

Repository for the user’s local files

> Vagrant@docker-test:~$ `cd ~`

This command shows the first directory after the user loga in.

***File path in Linux***

the file path can be accessed by using the command "pwd".

> Vagrant@docker-test:~$ `pwd file-name`

`/home/vagrant/IS601`

The pwd command lets you know the location of the mentioned file. 

***Using the tab key to complete file paths***

When you press tab, linux will complete the rest of the file name to the best of it’s knowledge.

> Pressing the tab button without any code will display every possible code available.

***Using up and down arrow for history***

Hitting the up arrow will let you cycle through your previous commands, while hitting the down arrow will let you navigate towards your more recent commands.
