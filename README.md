# my-first-repo
Repo for Vancouver Datajam 2021

Woo I'm making changes from my computer! 

001 let's make a conflict (and resolve it) 

003 now we're trying things on a separate branch, lets see if these show up in main or in our new branch

Here are the series of git commands I used: 

git add filename.md
git commit -m "description of changes I made" 
git push 
git status 

001: Making a conflict 

git add filename.md
git commit -m "committing changes from my editor" 
git pull #pulled the conflicting changes into my editor

#now I choose what I want to keep in my editor 

git add filename.md
git commit -m "resolved conflict" 
git push 

003: Making a separate branch
git checkout -b "branch_1" 
git push --set-upstream origin branch_1
git add filename.md
git commit -m "added a line to doc" 
git push 
#everything stays in branch 
#pull in Github to merge into main branch once you're done 
playing with code 
