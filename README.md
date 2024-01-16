# github-3.2-lim-wei-jie

###  What is GitHub Authentication
---
#### GitHub authentication is the process of verifying the identity of users and ensuring that they have the appropriate permissions to access and interact with resources on GitHub. Authentication is a crucial aspect of securing online platforms and preventing unauthorized access to sensitive information.
---

### What methods available to be implemented?
---
1. Username and Password
2. Personal Access Tokens (PATs)
3. SSH Keys
4. OAuth (OAuth 2.0)
5. GitHub Apps
6. Web Application Flow

---
**<ins>GitHub</ins>**
---
Remote Branch<br>
⬇️git fetch ⬆️<br><br>
Remote Tracking Branch <br>
(Local Cache of remote branch's content)<br>
⬇️git merge ⬆️git push<br>
Local Tracking Branch (Remote Repo Name,Origin)

1. git Clone "url"  //Clone Git hub repo to local repo

2. git remote  // check the current repo name
  * &nbsp;&nbsp;&nbsp;&nbsp;Git remote -v //check the path to push and fetch
  * &nbsp;&nbsp;&nbsp;&nbsp;Git remote rename "old" "new"  //rename
  * &nbsp;&nbsp;&nbsp;&nbsp;Git remote remove "name"  //remove git remote
  * &nbsp;&nbsp;&nbsp;&nbsp;Git remote add "name" "url"  //add name to github url and ready to push

3. git remote get-url --all origin // Check https or SSH clone

4. git push "remote" "branch" // origin(Github) master(Local)
  * &nbsp;&nbsp;&nbsp;&nbsp;git push "remote> "local-branch>:"remote-branch> // origin(Github) cats(branch):master

5. git Branch -r // View remote branch, local repository knows
  

6. git fetch "remote" "branch" // fetch a branch from a remote to local repo #not working dir
  * &nbsp;&nbsp;&nbsp;&nbsp;git fetch origin master // fetch latest from master on ori remote repo
  * &nbsp;&nbsp;&nbsp;&nbsp;git fetch origin // fetch all changes from the ori remote repo

7. git pull "remote" "branch" // fetch a branch from a remote to  working dir => git fetch + git merge
  * &nbsp;&nbsp;&nbsp;&nbsp;git pull origin movies // merge working dir with remote repo

8. git config // This command sets the author name and email address respectively to be used with your commits.
* &nbsp;&nbsp;&nbsp;&nbsp;git config –global user.name “[name]”
* &nbsp;&nbsp;&nbsp;&nbsp;git config –global user.email “[email address]”

9. git rm //This command deletes the file from your working directory and stages the deletion.
* &nbsp;&nbsp;&nbsp;&nbsp;git rm [file]

10. git show //This command shows the metadata and content changes of the specified commit.
* &nbsp;&nbsp;&nbsp;&nbsp;git show [commitID]

11. git tag //This command is used to give tags to the specified commit.
* &nbsp;&nbsp;&nbsp;&nbsp;git tag [commitID]

12. git stash
* &nbsp;&nbsp;&nbsp;&nbsp;git stash save //This command temporarily stores all the modified tracked files.
* &nbsp;&nbsp;&nbsp;&nbsp;git stash pop //This command restores the most recently stashed files.
* &nbsp;&nbsp;&nbsp;&nbsp;git stash list //This command lists all stashed changesets.
* &nbsp;&nbsp;&nbsp;&nbsp;git stash drop //This command discards the most recently stashed changeset.
* &nbsp;&nbsp;&nbsp;&nbsp;

13. Git remote  // check the current repo name
  * &nbsp;&nbsp;&nbsp;&nbsp;Git remote -v //check the path to push and fetch
  * &nbsp;&nbsp;&nbsp;&nbsp;Git remote rename "old" "new"  //rename
  * &nbsp;&nbsp;&nbsp;&nbsp;Git remote remove "name"  //remove git remote
  * &nbsp;&nbsp;&nbsp;&nbsp;Git remote add "name> "url"  //add name to github url and ready to push

14. git remote get-url --all origin // Check https or SSH clone

15. Git push "remote> "branch" // origin(Github) master(Local)
  * &nbsp;&nbsp;&nbsp;&nbsp;git push "remote> "local-branch>:"remote-branch" // origin(Github) cats(branch):master

16. Git Clone "url"  //Clone Git hub repo to local repo
---
### What are the 4 Github commands that you think you will use the most in the real project and why?
---
If there is no trouble shooting required then this 4 command
1. git add "file" or git add . // Adds changes in a file or all files to the staging area. 
2. git commit -m "Commit message" // Commits the staged changes with a descriptive message.
3. git push // Pushes committed changes to a remote repository.
4. git merge "branch-name" // Merges changes from the specified branch into the current branch.
---