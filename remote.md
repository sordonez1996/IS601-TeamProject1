#Git Remote Command

![Image of GIT]( https://www.w3docs.com/uploads/media/default/0001/03/a0eef303ddb3d0171bd61efc4451056173563b7b.png) 


•	The git remote command is designed for creating, viewing and removing connections to other repositories. Remote connections are considered to be bookmarks in other repositories, which are convenient names used for referencing URL that are not convenient enough.

•	The diagram below displays two remote connections from your repository into the central repository and into the repository of another developer. You can pass the origin to another developer and they will shortcut to other Git commands. As a result, you won’t have to reference the connections by their full URLs.

#Remote Add

•	To add a new remote, use the git remote add command on the terminal, in the directory your repository is stored at.
•	The git remote add command takes two arguments:
o	A remote name, for example, origin
o	A remote URL, for example, https://github.com/user/repo.git

For example:
$ git remote add origin https://github.com/user/repo.git
# Set a new remote

$ git remote -v
# Verify new remote
> origin  https://github.com/user/repo.git (fetch)
> origin  https://github.com/user/repo.git (push)


#Remote Remove

•	The git remote rm command has one parameter: The existing remote name;
•	The example will remove the gitlab remote. Note that the command will not delete the repository, just the local reference.
•	C:\Users\adm\repos\jersey-hello-world>git remote rm gitlab
•	To check that the remote was removed run the following command:
•	C:\Users\adm\repos\jersey-hello-world>git remote -v
•	github  https://github.com/admfactory/jersey-hello-world.git (fetch)
•	github  https://github.com/admfactory/jersey-hello-world.git (push)
•	The remote you just removed should not be in the list anymore.


#Remote Show


Source: 
Remote Add Source: https://articles.assembla.com/en/articles/1136998-how-to-add-a-new-remote-to-your-git-repo
Remote Remove Source: https://www.admfactory.com/how-to-remove-a-remote-from-git/
Remote Show Source: 

