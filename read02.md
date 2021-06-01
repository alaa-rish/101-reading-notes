# Remote Repositories
In order to collaborate on Git projects, you must interact with remote repositories, versions of a project residing online or on a network. You can work with multiple repositories, for which you can have read/write or read-only privileges. Teams can use remote repositories to push information to and pull data from.

## Cloned Repositories
As mentioned earlier, for cloned repositories, Git will automatically give the name “origin” to the server from which you cloned and the name “master” to your local branch.

## Seeing Your Remotes
By running the git remote command, you can view the short names, such as “origin,” of all specified remote handles.

By using git remote -v, you can view all the remote URLs next to their corresponding short names.

** $ cd example**

** $ git remote -v** 

