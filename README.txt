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
  
4. `Repository area` -> This area actually contains the details of all your previous registered version.
And the file in this area git alredy manages them and knows their version history.

5. `git add <file>` -> This command is used to move any file from working area to Staging area.

6. `git rm --cached <file>` -> This command is used to move any file from Staging area to Working area.

Note - Now lest say you want to move a file from staging area to repository area that means you need to actually
create a version and in git versions are actually managed using commits. You can say that commit is like one version,
one git commit like on git version. 

7 - `commit` -> Commit is a particular version of the project. It captures a snapshot of the projects staged changes and
create a version out of it. You will say that whenever you crate the commit then you have actually registered a bunch of changes
with git.

8. `git commit` -> registers staging changes to a commit.

9.`git log` -> list down all the commit of the repository.If you want to exit out of git log promt press `q`.
 
10. `git restore <file>` -> It removes all the files changes from the staging area to be committed. This can be useful,
if we did some dirty piece of code and now no more want it. Instead of deleting evey change line be line we can resotre or
you can say restore last clean version of the file.

11. `git restore --staged <file>` -> It removes file from changes from staging area to working area.
this only works if changes are in your staging area. 

12 `Difference beetween git rm and git resotre ` ->  
ans: if you want to move the whole file back to the untracked state, then we do git rm, otherwise if we just want the 
changes to be moved in working area or staging area then we do git restore.  