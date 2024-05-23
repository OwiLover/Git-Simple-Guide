# Git-Simple-Guide

Oh, you came here to learn some common git commands?

## How to make your git project.

1. git --version - this command will check if you have git on your machine

2. git init - this command initialise git in your respository (make sure that you've selected the right folder and that you actually have git installed on your machine)

### From now on everything in your folder can be tracked with git, to do this, after you've created some files or made changes, do the following:

1. git add . - this command tells git to start tracking everything in your current folder

2. git add -A - this commands adds every file from your project folder (where git was initialised)

### But it's not the time to change youк files! Firstly you have to "save" files state. To do this, look at the following commands:

1. git commit -m "Your commit comment"

#### What -m stands for? Well, this tells git that you're going to leave a comment right in the command! You'll still have to leave a comment even if you ignore the -m, but after the command.

### Oh no, I've broken everything!!! How to roll back?!?!?!

1. git reset --hard - This command delete everything you've changed and return every file to the state of the last commit you've made.
 
 ### What if I want to add extra functionality and want to have version without it?
 
 1. git branch - this command will list every branch you have (the current one will be marked with *)
 
 2. git branch Name-of-the-branch - this command will create a new branch where you can make some extra stuff
 
 3. git checkout Name-of-the-branch - this command will swap you to the selected branch. All git commits will now be saved for this branch, checking out to another branch will change everything to the state of the last commit in the selected branch, so don't forget to commit changes you've made before checkout!
 
 ### Okay, I've created so,e new crazy features and want to merge them with another branch
 
 1. git merge Name-of-the-branch - this command will merge two branches, all commits from the branch you've named in the command will now transfer to the branch you're sitting on, so remember to check your current branch before merging!

Those are the most common commands for git (Not GitHub, commands for GitHub will be added, but later)
