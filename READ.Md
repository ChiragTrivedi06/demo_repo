this repo contain all basic  git command :
 1. git status  
 2. git init                        -> to initialise git repo from a simple repo
 3. git clone  <address> <new_dir_name>
 4. git diff <file/folder name>     -> what is modified
 5. git commit -m "message"         -> to do final commit
 6. git log
    ex:git log -3 {latest three commit}
 7. git log -p                      -> latest commit and git diff {what change were made}
 8. git log --oneline               -> same as git log but in one line (only message and # id  )
 9. git log --stat                  -> all change with file name with line number
10. git show <sha-id>               -> show what change were made in particular commit 
11. git push -u origin <branch-name>
    ex:git push -u origin master
12. git add <file/folder name>      ->add file to track , put file in staging index
13. git add .                       -> add all file to track
14. git restore <file/folder name>  ->discard change in fill /remove modified file from working directory
15. .gitignore                      -> every file  in side will not track by git
16. git tag
17. git branch                      -> list all branch
18. git branch <branch name>        -> to create new branch from existing branch
18. git stash
19. git checkout                    -> to checkout branch / movement in branch
20. git merge 
21. git branch -d <branch name>     -> to delete branch
22. git commit -am "message"        ->use to add and commit simultaniously 
23. git remote add origin <repo-reme_link> 
 
undo commit:
24. git commit --amend
25. git revert <# id>
26. git reset --soft <# id>
