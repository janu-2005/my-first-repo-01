# my-first-repo-01

# creating a local folder
mkdir project1
# creating a file in project1 folder
cd project1
# copying the github repository to local folder
git clone https://github.com/janu-2005/my-first-repo-01
# adding file to the project1
nano hello_world.txt
# staging the file
git add hello_world.txt
# commit the file
git commit -m "first file"
# pushed the file into remote repository
git push -u origin main


New update


GIT ASSIGNMENT

Git Commands

# Checking the git version
git --version

#Giving credentials to git
git --config global user.name Pavani                     
git --config global user.email pavanigonthini@gmail.com

#Listing all the files and folders
ls  

#Creating a folder
mkdir project
cd project

#Initializing a repo
git init

#Creating a file
touch index.html

#Checking status
git status

#Adding to staging area
git add
git add .

#Committing to local repo
git commit -m "version1"

#Checking the history of git
git log
git log --oneline

#Branching
git branch
git branch login
git checkout -b login

#Merging
git checkout main
git merge login

#Remote repo
git remote add origin https://github.pavanigonthini.com
git remote -v

#Pushing to GitHub
git push -u origin main
git push

#Pulling the changes
git pull

#Cloning the repo
git clone https://github.pavanigonthini.com


#Shows unstaged and staged files
git diff
git diff --staged

#Create and switch to branch
git checkout -b login

#Saves all uncommitted changes'
git stash

#Restore stashed changes
git stash pop

#Delete all uncommitted changes
git reset --hard HEAD

#Restoring file changes
git restore file

#Revert a commit
git revert sha

#Tag a release
git tag -a v1.0.0 -m "release"



# SECTION:1 Basic Github operations.
1.Creating a new git hub repository in the git hub  named my-first-repo-01.
2.Added a README.md in the github by turning on the README.md.
Cloning the  github repository by using the command git clone https://github.com/janu-2005/my-first-repo-01.
To create the local folder we use mkdir project-1.
Change the directory to project-1 so that creating new files should be created in that folder. 
3.We can see the list of files in local folder by using the command ls.
4.Created a file using command touch then it will create a new folder named it as hello_world.txt for the file creation command is touch hello_world.txt.
5.After creating the file need to add command is git add . it will add all the files to the folder.
6.After the changes we need to commit the file then command is commit -m “hello_world.txt”.
After the changes need to push the file into github then used command is git push origin main.


# SECTION : 2 Branching and collabration 
1.Create a new branch called feature/add-logo . command git branch add-logo.
2.Switch to that branch and add a file named logo.png or any simple image file.command git switch logo.png.
3.Stage, commit, and push the feature/add-logo branch to GitHub. Command git add . ,git commit -m “add image file” , git push origin add-logo.
4.Create a pull request from feature/add-logo into main. Command git pull. Pull the request to downloading the changes into main.
5.Review and merge the pull request into main.command git switch main ,git merge.


# SECTION:3 github issues and project management.
1.Create an issue titled Fix broken links in README.An Issue is used to report, discuss, or track a task.

1. Report a Bug
Login button is not working

Create an issue so developers know there is a problem.

2.Assign the issue to yourself or a teammate and apply a suitable label.
Issue Title:
Fix broken links in README

Some links in the README file are broken and lead to invalid pages. These links need to be updated or removed to improve the documentation.

Assignee:
janu-2005

Label:
bug
3.Create a GitHub Project board with columns such as To Do, In Progress, and Done. Add the issue
you created into the project board.


# SECTION:4 Github actions and automation.
1.Create a workflow file at .github/workflows/ci.yml that runs automatically whenever code is
pushed to main. The workflow should run on Ubuntu and print a simple confirmation message such as CI is working!.
Created a workflow file named ci.yml inside the .github/workflows/ directory. The workflow is configured to run automatically whenever code is pushed to the main branch. It uses an Ubuntu runner (ubuntu-latest) and executes a simple command that prints the message "CI is working!"
2. Push a change that triggers the workflow. Verify the run in the Actions tab and describe the result.
After creating the ci.yml workflow file, I made a small change in the README.md file and committed the changes to the main branch. I then pushed the updated code to GitHub.
3. Create another GitHub Action workflow that deploys your project to a static hosting platform such as Netlify after a successful push to main. Use repository secrets for credentials and explain why secrets are needed.
created another GitHub Actions workflow to simulate the deployment of the project after a successful push to the main branch. The workflow is configured to run automatically whenever code is pushed to main. It uses an Ubuntu runner and executes the deployment steps.


# SECTION:5 Advamced github features.
1. Fork an open-source repository of your choice. Clone your fork locally and create a new branch for
a small improvement or fix.
Forked an open-source repository to my GitHub account and cloned the fork to my local machine. After cloning, I created a new branch named feature/update-readme to make a small improvement.
2. Make a small change in the forked repository, commit it, push it to your fork, and submit a pull
request to the original repository.
Made a small change in the forked repository, committed the changes, and pushed them to my fork. After that, I created a pull request to request that the original repository include my changes.
3. Add a Git submodule to one of your repositories. Commit and push the change, then explain what a
submodule is used for.
Added a Git submodule to my repository, committed the changes, and pushed them to GitHub. 
4. Enable GitHub Discussions in your repository. Create a discussion titled Suggestions for NewFeatures and add at least one thoughtful response

# SECTION:6 Best practices and versioning.
1. Create and push a Git tag named v1.0.0. Verify that the tag appears on GitHub and explain the difference between a tag and a branch.

2.Configure branch protection rules for the main branch so that pull request review is required before merging.explain how branch protection improves team work flows.

Configured branch protection rules on the main branch to require at least one pull request review before any changes can be merged. This ensures that all code changes are reviewed by another team member before becoming part of the main codebase


