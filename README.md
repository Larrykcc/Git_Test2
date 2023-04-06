# Git_Test2

hello odin 

<!-- ctrl + ` will open the command line>

<!-- git status checks status, if it's red and you
want to stage it go ahead enter "git add (name of file)"

+ you can add all of the files needing staging in the 
folder  with "git add .">

type git status once more to check..

FINALLY 

Finally, let’s commit all of the files that are in the staging area and add a descriptive commit message. git commit -m "Edit README.md and hello_world.txt". Then, type git status once again, which will output “nothing to commit”

PUSH YOUR WORK TO GITHUB
Finally, let’s upload your work to the GitHub repository you created at the start of this tutorial.

Type git push. To be more specific, type git push origin main.

type git status one more time to check “Your branch is up to date with ‘origin/main’. nothing to commit, working tree clean”.

Cheatsheet
This is a reference list of the most commonly used Git commands. (You might consider bookmarking this handy page.) Try to familiarize yourself with the commands so that you can eventually remember them all:

Commands related to a remote repository:
git clone git@github.com:USER-NAME/REPOSITORY-NAME.git
git push or git push origin main (Both accomplish the same goal in this context)
Commands related to the workflow:
git add .
git commit -m "A message describing what you have done to make this snapshot different"
Commands related to checking status or log history
git status
git log
The basic Git syntax is program | action | destination.

For example,

git add . is read as git | add | ., where the period represents everything in the current directory;
git commit -m "message" is read as git | commit -m | "message"; and
git status is read as git | status | (no destination).
