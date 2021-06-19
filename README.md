# git-sandbox
For experimenting with git

## Commands

**Local**

    git status
    git commit                                       - Will open editor
    git switch <branch>
    git checkout -b <branch>                         - Create a new branch
    git fetch && git checkout <branch>               - Get new branch (e.g. from BitBucket)
    git restore .                                    - Discard changes
    git merge <branch>
    git branch -d <feature_branch>                   - Delete a feature branch
    git commit --amend                               - Change last commit message
    git commit -a -m “message”
    git stash
    git stash pop
    git log [--graph]
    git rebase master                                - put current feature branch in front of master

View all Files in branch

    git ls-tree -r <branch> --name-only
    git ls-tree -r HEAD --name-only                  - current branch

**Remote**

    git push
    git pull                                         - fetch and merge remote branch with local branch
    git fetch                                        - get all data from remote repository (all branches)
    git remote -v                                    - list remote repositories
    git remote add <name> <Url>

**Configuration**

    git config --global user.email "joe@tuxn.com"
    git config --global user.name "Franz Maier"
    git config --system core.editor vim
