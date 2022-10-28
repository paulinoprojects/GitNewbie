# GitNewbie - Notes

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

# Git Commands & Workflow
- <b>git clone</b> -> Bring a repo that is hosted somewhere like GitHub into a folder on your local machine
- <b>git init</b> -> Creates new repo (.git cirectory with subdirectories for objects, files, tags, etc.) An initial branch. 
- <b>git add</b> -> Track your files and changes in Git
- <b>git commit</b> -> Save your files in Git
- <b>git push</b> -> Upload Git commits to a remote repo, like GitHub, BitBucket, GitLab
- <b>git pull</b> -> Download changes from remote repo to your local machine, opposite of push command


---------------------------------------
To start a new Git Repo for an exisiting code:\
$ cd /path/to/my/codebase\
$ git init      (1)\
$ git add .     (2)\
$ git commit    (3)
