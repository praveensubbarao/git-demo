# git-demo
Git commands demo

## git commands

Git Help Commands
Help commands here.
 
Lecture Command Listing
git help
git help config
 
Command Reference
Getting general help:
git help
Help Command Syntax -- getting help about a specific Git command:
git help command
Git Configuration Commands
What's the current directory (present working directory)?
pwd
Git Config (Global/User-level) Syntax
git config --global setting value
Configure User and Email
General Syntax:
git config --global user.name "Your Name"
git config --global user.email "you@someplace.com"
Example using course author's information:
git config --global user.name "Jason Taylor"
git config --global user.email "jason@jasongtaylor.com"
Listing All Global Configuration Settings
git config --global --list
Seeing Git's User-based Config file
cat ~/.gitconfig
Git Starting Commands
 
Lecture Command Listing - Fresh Start
pwd
cd projects/
git init git-demo
 
Lecture Command Listing - Start with Existing Project
pwd
cd projects/
cd website/
ls
git init
 
Command Reference
Present Workding Directory
pwd
Change Directory
cd folder-name
Git initialization
git init [project-name]
project-name parameter is optional. If not supplied, Git will initialize the current directory.
Git Working Locally Commands
 
Lecture Command Listing - Working Locally, Part One
pwd
git status
mate README.md
git status
git add README.md
git status
git commit -m "Adding some ipsum"
clear
git status
mate README.md
git status
git commit -am "Adding more ipsum"
git status
 
Lecture Command Listing - Working Locally, Part Two
pwd
git status
clear
mate index.html
git status
git add index.html
git status
mate README.md
git status
clear
git status
git add README.md
git status
git commit -m "A few changes for the website"
clear
mate README.md
mate index.html
git status
git add .
git status
git commit -m "A few more changes for website"
clear
mate README.md
git status
git add README.md
git status
git reset HEAD README.md
clear
git status
mate README.md
git checkout -- README.md
mate README.md
git status
 
Command Reference
Express Commit for Tracked files
git commit -am "Awesome commit message"
Use the -a parameter with the git commit command to directly commit newly modified tracked files. Warning: Only do this for small changes. Tracked files are files that have been previously added to Git (committed or staged).
Adding All Changed Files
git add .
The period parameter for the git add command will recursively add all new and newly modified files.
Unstage File
git reset HEAD file-name
Following the above command will "unstage" the specified file from Git's staging area (aka index).
Backout Working Directory Changes
git checkout -- file-name
Following the above command will back out any changes made to the specified file and replace it with the version last committed in Git


