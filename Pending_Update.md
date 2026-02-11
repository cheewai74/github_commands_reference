```
# To know which email is configured for a specific repository, go to the repository folder and run each line separately
git config  # lets you configure different options for git
git config user.name
git config user.email

git config --global user.name "Tom"
git config --global user.email "Tom@gmail.com"

# Would you like to know what is configured for each level? Just add the specific option after config command:
git config --system user.email
git config --global user.email
git config --local user.email


# Change author email
git commit --amend --no-edit --author="New Name<new_email@free.com>"

git push --force-with-lease

git commit --amend --no-edit
git push -f

git pull --rebase origin main


git init
git add .  # Add all files
git commit -m "First Commit"
git log

git reset --hard origin/my_remote_branch

git switch # use to move between branches

git stash apply # get an item from stash without removing it.

git restore . 


git rm  # delete a file

```
