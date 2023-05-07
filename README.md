# Demo - Local Repo
 How to:
1) run cmd:  git status
You can see info regarding any untracked files
2) Now to add any untracked files, you can either do:
	run cmd: git add <filename> (if it is specific untracked file you are trying to add)
    	
	OR

	run cmd: git add . (if you want to add all untracked files)
3)run cmd: git status again to confirm that the files you want added are now tracked
4)run cmd: git commit -m "<title of commit>" -m "<desc of commit>"

At this point you would want to push this into Github, but before you can you need to establish the repo on Github

5)Create repo on github

6)Get the SSH key

7) run cmd git remote add origin <SSH key>

8) run cmd: git remote -v (this allows you to see any remote repositories that you have connected) to this repo

9) now you can run cmd: git push origin main

10) to set a default directory to push to:
	run cmd: git push -u origin main


## Now we are branching

git branch - shows you all the existing branches
git checkout -b <branch name> creates a new branch
git checkout <branch name> puts you on the branch

