# Java Projects <-> GIT 

# AndroidStudio 3.1 -> 

## 1. Create Android Project

Create Android Project in Android Studio.

e.g.: _https://github.com/myUserName/myFirstAndridGitProject_

## 2. Create GIT Project

Create Project with README.md, .gitignore (Java) and LICENSE in _https://github.com/myUserName_

with same name as in AndroidStudioProjects: _myFirstAndridGitProject_ 

## 3. Connect local project with remote project on https://github.com

1. Open terminal in _~\myFiles/AndroidStudioProjects/myFirstAndridGitProject_

2. Create local git with command:  
__>> git init__

3. Set remote origin (_https://github.com/myUserName/myFirstAndridGitProject_) in local repository with command:  
__>> git remote add origin https://github.com/myUserName/myFirstAndridGitProject__


4. Verify remote repository with command:  
__>>git remote -v__

5. Pull files from github.com repository to local repository with command:  
__>> git pull origin master__

6. Copy customized .gitignore from _https://github.com/github/gitignore_  
into your local project directory _~\myFiles/AndroidStudioProjects/myFirstAndridGitProject_  
or take my version, with drops more files from _https://github.com/ReinhardFink/ProjectToGithub/AndroidStudio.gitignore_.

7. View local changes with command:  
__>>git status__

8. Add local changes to git with command:  
__>>git add .__

9. Commit local changes with command:  
__>>git commit -m "added Android Project to git"__

10. Push local changes back to remote origin (_https://github.com/myUserName/myFirstAndridGitProject_) with command:  
__>>git push --set-upstream origin master__
