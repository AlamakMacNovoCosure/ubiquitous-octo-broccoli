# ubiquitous-octo-broccoli

## Github Authentication Method
- **Personal access token** by generating personal token from github
- **Username and password with two-factor authentication (2FA)**
- **Passkey** it satisfy both password and 2FA
- **Https** via web browser, only for enterprised account
- **SSH** via setting  public key of local machine into github ssh agent

## 15 Github Commands and they usage
- **git config** sets the configuration values of the project. Such as the username, email, file formats, and more.
- **git init** initialise a git repository and create the initial directory whether the project is new or already exists.
- **git clone** create a repository copy from a remote source.
- **git add** add file changes in your working directory to your remote version of the repository.
- **git rm** remove files from your index and your working directory so they won’t be tracked when running git add or git commit.
- **git commit** takes all the changes in your working directory and creates a new commit object pointing to it.
- **git satus** shows the status of files in the index versus the working directory so you can see all changes made.
- **git branch** multiple people work on the same project, they often create their own branches. Git branch lists existing branches, including remote ones, if ‘-a’ is added or makes a new branch if a branch name is provided.
- **git merge** Once you or a teammate is done working on a branch, you probably will need to merge it to the main branch. Git merge will do so and automatically creates a new commit if no conflicts are found.
- **git reset** found a bug that completely ruined your code, you can go back to the latest working version of your working directory using git reset.
- **git tag** tag a specific commit with a simple handle to track the changes done to the project efficiently.
- **git pull** want to work on the recent version of a repository, you can fetch all the files from the remote repository, merge them and proceed to work from there.
- **git push** changes have been tested and you need to add them to the original remote repository, git push will add all the modified local objects to that remote repository.
- **git log** help track all commits on a branch and their corresponding details.
- **git archive** create a tar or zip file of the contents of a single tree from any repository.

## 5 most likely use commands (assuming no branch created)
- **git clone** copy a repository and work on it
- **git add .** add file changes from local to remote repo
- **git commit -m "commit message"** create a new commit object pointing to it
- **git push** changes made, tested and add all modified local object to remote repo
