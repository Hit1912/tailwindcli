GIT COMMAND

config setup
SET:-
git config --global user.name ""
git config --global user.email ""
git config --list

UNSET:-
git config --global --unset user.name ""
git config --global --unset user.email ""

1.  git branch                                    --  Check current branch
2.  git branch new branch name                    --  Create a new branch
3.  git init                                      --  git init creates a new Git repository in your project folder.
4.  git status                                    --  git status tells you the current state of your project.
5.  git add .                                     --  Put ALL changed files into the staging area
6.  git commit -m "your msg"                      --  Permanently save the staged changes with a message
7.  git log                                       --  Check history
8.  git checkout branch name                      --  branch switched
9.  git push origin branch name                   --  Sends your local commits to a remote repository (like GitHub).
10.  git pull origin branch name                   --  Fetches changes from the remote repo and merges them into your local branch.