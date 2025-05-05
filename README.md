## End to end ml project

GitHub repo setup

1. create an empty repo (don't check README.md)
2. create a folder"projectname" on local machine in specific folder (say 'D:')
3. open cmd
4. go to D:
5. cd projectname
6. type = code .   (it will open this projectname folder in vscode)
7. in vscode open its terminal
8. create environment in that projectname folder, so all the library will be there in that folder 
9. conda create -p venv python==3.8 -y  ('venv' name of environment, '-y' means yes to all permissions)
10. in future we will be creating our files in folder(projectname) and not inside env
11. To activate this environment, use conda activate D:\EndToEnd_Project\venv    .    To deactivate an active environment, use conda deactivate
12. type = git init
13. create a README.md on left side of VSCODE
14. type = git add README.md             (add means make changes)
15. type = git commit -m "First Commit"  (commit means save changes)
16. type = git status
17. type = git branch -M main            (rename branch from master to main)  
18. type = git remote add origin https://github.com/Ashking21101/EndToEnd_Machine_learning_Project.git
19. type = git remote -v
20. type = git config -global user.name "Ashking21101"
21. type = git config -global user.email "ashishtak21101@gmail.com"
22. type = git push -u origin main       (push from origin{my pc} to main{git}, means push in git repo)