1. Create project directory (folder)
2. Open project directory via 'Open Folder' in VS Code (folder)
3. Open the 'terminal' in VS Code
Type below command in terminal:
4. git init
   // Create git in directory

5. git remote add origin git@github.com:kenny633/repo-name.git
   // Link the github repo
   // git remote add [remote-name] [repo-ssh-link]

6. git remote -v
   // Check the remote added
   // origin  git@github.com:kenny633/repo-name.git (fetch)
   // origin  git@github.com:kenny633/repo-name.git (push)

   /* setup git end */
Upload changes to git (Push)
7. git add .
   // To prepare the content staged for the next commit

8. git commit -m "type message here"
   // Create a new commit

9. git push origin master
   // Update all new commits to remote repo
