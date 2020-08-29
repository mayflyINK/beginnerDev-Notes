# Notes on Git and GitHub
## Tools you will need:
- install Git for Windows, which includes Git Bash (Bourne Again Shell)
 - Unix shell emulator for Windows (terminal window)
- select preferred code editor and default settings.

References:
https://gitforwindows.org/
https://www.atlassian.com/git/tutorials/git-bash
https://www.youtube.com/watch?v=qdwWe9COT9k

Github Notes
- git is version control software
- github is a web service running git
- repository - is a 'project' of stuff
 - initialize with README file selected
- commit - is 'save', or commit to changing file
- add a descirption to each commit for context when collaborating
- a commit generates a unique identifier (hash, alphanumeric string) seen in commit history page
- branch creates a new version, seperate from master
- pull request from master, merges work from branch
- fork makes another instance of the same project in another repo
- pull request from a fork, is a request for the orginal repo owner to merge any changes from the fork
- issues are a seperate interface layer ontop of git that allow others to comment and raise issues
 - only repo owner and issue creater can close issue
 - reference issue in commit comment "fixed issue #no" to close issue on commit
 - can reference commit hash (url string) in issue comment
 - can add images to issue
- clone - copy repo to local machine

Getting started with gitbash
- Open gitbash
- cd $USER - to naviate to windows user directory
- cd [drop folder - location path] eg. desktop
- pwd - to check "workind directory
- git - check git is installed, running on machine
- clear
- will get warning to sign in, copy and paste git config items (1 at a time)
    - git config "username"
    - git config email
- create repo on github - copy an HTTP address
- git clone [HTTP address]
- cd [cloned folder path]
- make changes to files in folder
- git status - get repo folder info
- git commit -a -m "this is commit message" - argument all and commit message (git commands need arguments) 
- git config --list - will display local git config settings
- git log - see history of git commits
(- :q - escape out of VIM text editor)
- git remote
 - list remote locations associated with project
 - git remote -v - argument verbose
- git push origin master
 - enter username and password

**Make folder on local machine a repo on github**
- cd [folder directory path]
- git status - check folder git status
- git init - initilises git repo
- git status - check status of repo
- new files needed to be added to the staging environment before commit
 - git add [file name] - adds file to staging environment
 - git add . - adds all files that have been changed
- git commit - to commit new files from the staging environment to repo
- push to github, need to create a new repo (remote) on github
 - don't initialise with readme file, make empty repo 
- git remote add origin [github repo path/url] - ("origin" is just convention could be named anything)
- git push origin master (if not "origin" use name from above)
- if make a change on github website, use terminal to
- git pull origin master

**Github Pages**
- make repo with README
- make new branch named "gh-pages"
- change default branch - settings > branches > default branch
 - select "update default branch"
- delete "master" branch
- go to settings - GitHub Pages to find url
- make new file - index.html

**Merge Conflicts**
//TODO

**Git Remotes**
- git remote remove origin
- git remote add github [github path/url]
- to add someone elses remote
 - git remote add [remote name] [github path/url]
- git branch [branch name] (where "grahics" could be any name)
- switch th branch
 - git checkout [branch name]

**Unix command line prompts**
 - cd = change directory
  - cd $USER = windows user directory
  - cd .. = return to previous directory
  - cd [drop folder - location path] = drag and drop folder from explorer into terminal window
 - start . = open browser window ("." is current directory)
 - pwd = print working directory
 - ls = lists
  - ls -all = folder/file meta data
 - clear = clears terminal window
 - tab = autofill directory name
 - up/down arrows = scroll through previous commands prompts
- git add . -A (add and delete everything)
