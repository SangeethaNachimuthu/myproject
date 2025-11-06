git init == Initializes a new git repository in the local/current directory.
git add == Adds a new file into the staging area (Specify the file name in the command).
git add . == Adds all the new files to the staging area.
git status == Specifies the status of the current directory and the staging area.
git commit -m "message about the commit" == Saves the changes in the repository.
git log == Displays the history of commits.
git log --oneline == Displays a oneline/compact history of the commits.
git diff <version id> <filename> == Compare the current file with the mentioned version    file and shows the difference between two files.
git restore <filename> == Discards the latest changes in the working directory.
.gitignore == It is a file without any extension. If we want to ignore some files from git, we can add those file names in the .gitigonre file. So the mentioned files will be ignored by git.
git remote add origin <url> == Connect local Git repository to a remote repository on GitHub.
git branch -M main == Change the current branch to main.
git push -u origin main == Push the local repository commits to the remote repository on GitHub.
git clone <url> == It clones the git repository to our local repository.
git remote -v == To see which remote GitHub is connected.
git branch == Displays the current branch name of the repository.
git branch -a == Displays the all the branches of the repository.
git pull == To fetch the latest changes from the remote to local.
git checkout <branch name> == To change/switch to the specific branch.