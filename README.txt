1. `git init` -> Powers to your folder to be managed by git, and initialises a new empty 
repository. It also create a .git folder that has all the relevant logic to manage version
of your project. 

2. `Working Area` -> There can be bunch of files that are not currently handled by git. It means
that changes done or to be done in those file are not managed by git. A file which is in working 
area is considered to be not in the staging area. When we do `git status` and we see
 a bunch of `untracked files` then these are actually  called to be in the working area.

3. `Staging Area` -> It is tell to us what all files are going to be part of the next version 
that we will create. This staging area is the place where git knows what changes will be done 
from the last version to the next version.
  git add <file> -> This command is used to move any file from working area to Staging area.
  git rm --cached <file> -> This command is used to move any file from Staging area to Working area.   

