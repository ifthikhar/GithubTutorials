GITHUB tutorials with commands

1. git add . (add all the files in the master branch)
2. git add <filename> (all specific file using names)
3. git branch login 
- This will create a new branch called login and developer can work on this branch seperatly.
- This files added to this branch won't be commited to master branch until , it it merged.
4. git merge login
- When developer is in master branch and need to merge login branch, this command is used.
5. git checkout master 
- Using this command, developer can move out of current branch and go to master branch.
6. touch .gitignore 
- Used to add file which will be added to branch when commit and add is performed.
7. git commit -m 'comment to be added'
- Will commit all the added file to commit stage.
8. git remote add origin 'remote git repository'
- This  will add the master branch which is currently in use to origin remote endpoint.
9. git push origin master
- command for copying the local master branch files to remote branch endpoint.
10. git clone remoterepository url
- For cloning the repository present in url like github.