
| Step  | Command | Description|
|---|---|---|
|1. Switch to the master branch  | git checkout master            |You need to be on the branch where you want to apply the commit.                                                                        |
|2. Update your master branch    | git pull origin master         |It's always a good practice to have the latest version of the branch you're moving the commit to.                                       |
|3. Find the commit hash         | git log project-pre-los-dev    | Look through the commit history of the project-pre-los-dev branch to find the specific commit you want to cherry-pick. Copy its hash.  |
|4. Cherry-pick the commit       | git cherry-pick <commit-hash>  | This command applies the commit, identified by its hash, to your current branch (master).                                              |
|5. Push the changes             | git push origin master         | Once the cherry-pick is successful, you can push the commit to the remote master branch.                                               |


commit <commit hash> </br>
Merge: hash  </br>
  
If unsuccessful:
git cherry-pick -m 1 <commit hash> </br>
