
# git-tutorial
all about git and GitHub notes.

git commands
1. git config --global user.name "AliBaltistani"
2. git config --global user.email "muhammadalid15@gmail.com"
3. git config ls
4. ls -a
5. git status 
6. git clone https://....(repo url)
7. git add file_name
8. git add . (for all changed files)
9. git push origin main (publish into main branch)

==============
================
Init Command
=============
=================

init used to create new repo
1. git init
2. git remote add origin <- link ->
3. git remote -v (to verify remote)
4. git branch  (to check branch)
5. git branch -M main (to rename main)
6. git push origin main  or (branch name)
7. git push -u origin main (-u flag is used to alis repo name)

==============
Commands for Branches 
=================

git branch (to check banches)
git branch -M new_name (to change Branch name)
git checkout feature1_branch (to shift branch)
git checkout -b new_branchName (to create new branch)
git -d branch_name (to delete branch)


==============
================
Merging Code
=============
=================

# Way 1
 1. git diff branch_name
 2. git merge branch_name

# Way 2 (Create Pull Request)
 1.

==============
================
Merging Conflicts
=============
=================
 1. git diff branch_name
 2. git merge branch_name
