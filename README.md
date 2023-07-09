# github-3.2-chris
This is the assignment for Module 3.2

-----------------------------------------------------------------

# Assignment for Module 3.2
### _GitHub_
[![GitHub](https://logosmarcas.net/wp-content/uploads/2020/12/GitHub-Simbolo.png)](https://github.com/apkiys/github-3.2-chris)

#### what is GitHub Authentication and how what methods available to be implemented?
GitHub Authentication is a way for people to prove their identity and access certain features on GitHub, a platform for hosting and collaborating on software projects. It ensures that only authorized individuals can perform actions like uploading code or accessing sensitive information.

- There are different methods available for authentication on GitHub:
- Username and Password: Users enter their username and password to log in. It's the most basic method, but it's not very secure.
- Personal Access Tokens: Users can create special tokens instead of using their passwords. These tokens have limited permissions and can be used for automated tasks.
- OAuth Apps: Developers can create special applications that connect to GitHub using the OAuth protocol. It allows users to authorize the app to access their GitHub account without sharing their password.
- GitHub Apps: These are powerful apps that can be installed directly on repositories or organizations. They have their own authentication tokens and can access GitHub on behalf of users.
- Web Application Flow: This method involves users being redirected to GitHub to log in and authorize an application. After authorization, they are sent back to the app with a special code.
- Device Flow: This method is for devices like TVs or game consoles with limited input. It displays a code on the device and asks the user to enter it on a GitHub webpage to authenticate.
- These methods provide different levels of security and control depending on the needs of the user or application.

-----------------------------------------------------------------

#### The following are the commands I have used in familiarising with Git and GitHub:
- (Create remote repository in GitHub) gh repo create github-3.2-chris --public --description 'This is the assignment for Module 3.2' --add-readme
- (Download repository into local) git clone git@github.com:apkiys/github-3.2-chris
- (Checking of branch and git status) git status
- (Create and change to new branch) git checkout -b update-readme-1
- (List all branches) git branch
- (Add changes to staging area in branch) git add .
- (Commit changes) git commit -m 'Create changes on README file on update-readme-1 branch'
- (Push changes to remote repository branch) git push origin update-readme-1
- (Changing to main on local repository) git checkout main
- (Pull down changes from remote repository) git pull origin update-readme-1
- (Checking on which branch) git branch
- (Alternative merge of main and update-readme-1 branch) git merge update-readme-1
- (Push changes to remote repository main) git push origin main
- (Checking remote without merging into local) git fetch git@github.com:apkiys/github-3.2-chris
- (Delete newly created branch locally) git branch -D update-readme-1
- (Delete newly created branch remotely) git push -d origin update-readme-1
- (Add changes to staging area in branch for new contents) git add .
- (Commit changes) git commit -m 'Create changes on README file on update-readme-1 branch x 2'
- (Undo changes to commit) git reset HEAD~
- (Add changes to staging area in branch for new contents) git add .
- (Commit changes) git commit -m 'Create changes on README file on main'
- (Push changes to remote repository main) git push origin main
-----------------------------------------------------------------

#### What are the 4 Github commands that you think you will use the most in the real project and why?
The following 4 commands would most likely be used very often due to basic usage for git: To have collaborative work using version control.
- git checkout (for changing between branches during production)
- git add (for putting changes to staging area)
- git commit (for preparing snapshot of local repository)
- git push/pull (for pushing or pulling changes to or from remote repository)
-----------------------------------------------------------------

git config --global --add safe.directory C:/******/github-3.2-chris
git remote set-url origin git@github.com:apkiys/github-3.2-chris.git