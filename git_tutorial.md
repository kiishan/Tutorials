## Git Tutorial

### Contents

    1. git init
    2. git add
    3. git status
    4. git commit
    5. git push
    6. git pull
    7. git clone

### Creating a project

1. Create Project folder & files
    - Right click folder select git bash here
    - Create files using __touch__ command
    - Edit files use editors like Atom, VS Code

2. Initialize folder as git repo
    - git init

3. Add name and email to git
    - git config --global user.name 'Kishan Kumar'
    - git config --global user.email 'Kishan Kumar'

4. Add files to staging area [Changes to be commited]
    - git add .
    - git add .ext
    - git add fileName

5. Check staging area for tacked and untracked status
    - git status

6. Remove files from staging area
    - git rm --cached fileName

7. commit changes
    - git commit
    - add comments: 
        - vi editor edit mode > press i'
        - exit edit mode press esc'
        - 'save changes pres wq: enter'
    - git commit -m 'Comment'

8. Exlude files/directories from being added to repo
    - create .gitingnore file
    - add file and dir names to it

9. creating branch for enhancement projects
   - git branch branchName

10. Move to branch
    - git checkout branchName

11. Merge branch to master
    - git merge branchName

12. Add remote repository
    - git remote add origin https://repo.git

13. push your local repo to remote repo
    - git push -u origin master
    - enter usrname pass

14. Clone remote repos to system
    - git clone link
15. update local repo from remote repo
    - git pull

__Pretty much everything that we will use__


