# Git & Github for Newbies

<b>Git</b>: Free open-source distibuted version/source control management system to collaborate, track, investigate the management of changes to documents, programs, web sites, and other collection of information

Install Git, then In Windows, Linux, MacOS command line, use <b><i> "git" </b></i> to view a list of commands. If CLI errors, Git was not successfully installed on your machine.

## Terms  
- <b>Directory</b> -> Folder
- <b>Terminal & CLI</b> -> Interface for text commands
- <b>Editor</b> -> Integrated Development Environment (IDE/SDK) or a text editor to write your code
- <b>Repositroy (repo)</b> -> project or folder where your projects are kept
- <b>Branches </b> -> 
  -   A branch is a parallel version of a repo, but does not affect the primary (main/master) branch.
  -   Allows you to work without disrupting live version or to revert back to original if you mess up.
  -   When you made your changes, you can merge your branch into the primary branch to publish your changes
  -   Remove branch refers to GitHub to view <b>git remote -v </b>
- <b>Working Directory</b> -> Your current work
- <b>Staging Area</b> -> <b>git add</b> command will push working directory code to staging area for review.


# Git Commands & Workflow
- <b>git clone</b> -> Brings/pulls a repo that is hosted somewhere like GitHub into a folder on your local machine
- <b>git init</b> -> Creates new repo on you local machine (.git directory with subdirectories for objects, files, tags, etc.) An initial branch. 
- <b>git add</b> -> Track your files and changes in Git and adds code to staging area.
- <b>git commit</b> -> from the staging area, commits/push your files in the main branch.
- <b>git push</b> -> Upload Git commits to a remote repo, like GitHub, BitBucket, GitLab
- <b>git pull</b> -> Download remote repo to your local machine, opposite of push command
- <b>git log</b> -> shows a list of all the commits made to a repo, hash, metadata, etc
- <b>git pull</b> -> 


---------------------------------------
<b>To start a new repo on your local machine:</b>\
  $ cd /path/to/my/codebase\
  $ git init - creates your repo in the git\
  $ git add -m *insert important message* puts code in staging area\
  $ git commit -m *insert important message* push code to main branch on Github
