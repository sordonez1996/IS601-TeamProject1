#Git Merge Command


•	The git merge command integrates the independent lines of development into a single branch. The git merge command goes hand in hand with the git checkout command to select the current branch and the git branch command with the -d flag to delete the obsolete target branch. Read about these commands in our previous chapters.


•	The primary use of git merge is to combine two branches. It is also used to merge multiple commits into one history. In the following illustration, git merge takes two branch tips and finds a common case commit between them. The common base commit creates a new commit that merges the changes of the sequence of each merge commit. Here we have two branches: a master and a stage. We should merge the stage branch to the master branch.

•	Merge commits are unique because they have two parent commits. Git automatically merges separate histories when a new merge commit is created. It will not combine the data that is changed in both histories. This is what is called “version control conflict”.


![Image of GIT]( https://www.w3docs.com/uploads/media/default/0001/03/10070f6e0b1755e3014b22658f32e7c6864b8e1d.png) 

![Image of GIT Merge]( https://www.w3docs.com/uploads/media/default/0001/03/492bbdd4d1c256ad4b07c9a042fd18fca353b1cc.png) 



Source: https://www.w3docs.com/learn-git/git-merge.html

