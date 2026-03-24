# to send files from GitHub to VS Code
# Type in the Terminal (on Computer or VS Code...)

1) git clone <SSH key> to copy the files on GitHub to VS Code

2) cd <name of the folder> to change directory to the folder

3) ls means listing everthing in the directory including hidden files and folders

4) git status shows all the files that were updated or created or deleted, but haven't saved in a commit yet.
Look at ImplementFile.html as example for number 4

5) git add
1. git add . stages all changes
2. git add <file> stage a file
Example: git add ImplementFle.html will add the ImplementFile.html to the branch
3. git add -A or git add --all to save all changes from the files including the deleted ones

6) git commit -m "message" commit changes with messages on GitHub if succeed
Example: git commit -m "sdfasf"
even more: git commit -m "sdfa asf" -m "asdf    " -m " asdfafsa sw"

* However, when you clone from GitHub to VS Code, whatever happens to clone will never change the original one
- for example this file Example1Implement.md, you read this file in VS Code as a clone, so if you change something in this file, it will never change the one on GitHub
But you still can see the changes in the clone files in your desktop
- the file Index1.html was not created from GitHub, so when you create this file in VS Code in the directory, you can add it to GitHub. But when you added it to GitHub, you can't make change in this file. You can go to Source Control to see it
+ But if you want to make change, got to Source Control, and click Sync

* You have to commit in Source Control if you want to make changes to the directory on GitHub through VS Code