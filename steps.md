# Typical Workflow
1. Clone the repository
2. Create a new branch from the `main` or another branch
3. Make your changes
4. Push the branch to the remote repo
5. Open a Pull Request
6. Merge the changes
7. Pull the merged changes into your local `main` branch
8. Repeat from step 2


---


## local repo (git)
    1. git init
used to initialize the project.


    2. git config --global init.defaultBranch main
used to rename default branch name master -> main (globally)


    3. git status
used to check the status of git repository


    4. git branch -m master main
used to rename branch master -> main


    5. git add readme.md
used to add readme.md file into the stage


    6. git commit -m 'Add readme.md file'
used to commit (all files in stage) with message _'Add readme.md file'_


    7. git add .
used to add all files into the stage


    8. git log
used to view the log history of committed stages


    9. git checkout dc5a9e16496e8f6ca880b7535b9af7fa155e2dfd
used to move to the selected stage _(dc5a9e16496e8f6ca880b7535b9af7fa155e2dfd)_


    10. git checkout main
used to move to the main stage




## remote repo (github)

    11. git remote add origin https://github.com/abu-hamzah-dev/learning-git.git
used to connect local repo (git) with remote repo (github) with alias 'origin' (default alias)


    12. git push -u origin main
used to push all files in stage main


    13. git branch branch-name
used to create branch with name _'branch-name'_


    14. git checkout branch-name
used to change selected branch to _'branch-name'_


    15. git checkout -b feature-branch
used to create branch and change directly the selected branch into 'feature-branch'


    16. git add .
used to add all files in to the stage


    17. git commit -m 'modify readme & add steps.md'
used to commit (all files in stage) with message _'modify readme & add steps.md'_


    18. git push -u origin feature-branch
used to push current stage of local branch _'feature-branch'_ into remote branch _'feature-branch'_ (this makes establish a tracking relationship between local repo and remote repo, so in the future you just need to use `git push` and `git pull`)
 

## merging & resolving merge conflicts
