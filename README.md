# Connect-your-local-project-folder-on-Github
Connect your local project folder on Github

https://gist.github.com/mindplace/b4b094157d7a3be6afd2c96370d39fad

https://www.softwarelab.it/2018/10/12/adding-an-existing-project-to-github-using-the-command-line/

The screen you should be seeing now on Github is titled 'Quick setup — if you’ve done this kind of thing before'.

Copy the link in the input right beneath the title, it should look something like this: https://github.com/mindplace/test-repo.git This is the web address that your local folder will use to push its contents to the remote folder on Github.

Go back to your project in the terminal/command line.

In your terminal/command line, type git remote add origin [copied web address]

Example: git remote add origin https://github.com/mindplace/test-repo.git

### fatal: protocol '[https' is not supported

then add as 

Example: git remote set-url origin https://github.com/sahujaunpuri/Medix-v3.0-The-Pharmacy-POS-Management-System.git

Push your branch to Github: git push origin master

Go back to the folder/repository screen on Github that you just left, and refresh it. The title 'Quick setup — if you’ve done this kind of thing before' should disappear, and you should see your files there.




Create a new repository on GitHub. You can also add a gitignore file, a readme and a licence if you want
 Open Git Bash
Change the current working directory to your local project.
Initialize the local directory as a Git repository.
git init
Add the files in your new local repository. This stages them for the first commit.
git add .
 Commit the files that you’ve staged in your local repository.
git commit -m "initial commit"
 Copy the https url of your newly created repo
In the Command prompt, add the URL for the remote repository where your local repository will be pushed.

git remote add origin remote repository URL

### fatal: protocol '[https' is not supported

then add as 

Example: git remote set-url origin https://github.com/sahujaunpuri/Medix-v3.0-The-Pharmacy-POS-Management-System.git

git remote -v
 Push the changes in your local repository to GitHub.

git push -f origin master
That’s all
