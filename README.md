### These are some of my learning from understanding the git version comtrol system 

## Important commands 
1. git --version : checks current version
2. git init : initialize git for a particular folder 
3. git status : gives info about tracked folders 

* cd .. -> go back one folder in bash

4. touch -> used to create a file 
5. git add -> used to track a specific file 
6. git rm --cached <filename> -> un stage a file  

7.git commit -m -> used to commit a file to repo , no longer tracked by status (requires message)
8.git log --oneline -> log the git commits 

9.git config --global user.email/user.name 

10. git branch -> points to current branch
11. git branch <new-branch-name> -> creates new branch 
12. git checkout/switch <branch to be moved to> -> points to a new branch
13. git checkout -b /switch -c <new branch> -> creates and shifts to the branch 

14. git merge <branch to be merged to master> -m "message" -> merger branch 
15. git branch -d <branch to be deleted> -> delete branch

16. git diff - 
(a-> initial ver of file ,represented by ---  ,
 b-> final ver of file , represented by +++)

17. git diff --staged -> shows diffrence in the file 

18. git stash -> sitching branch (w/o commiting)
19. git stash pop -> bring back those changes which were stashed 
20. git stash list -> shows current stashed changes 
21. git stash apply <stashname> -> apply the required stash

22. git restore <filename> -> get backs to the last commit version 
