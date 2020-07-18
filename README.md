HOW TO MAKE VENV PROJECT
- make git repository in github with python template
- git clone "url" 
- navigate to project folder
- make README.md and add to repo

- make env (virtual environment) using " virtualenv venv"
- activate venv with " source venv/bin/activate" 
- immediately put venv folder in gitignore if it wasnt already in the github python template 
- commit changes with " git commit -m 'message' " 
- push changes to master with " git push -u origin master " 

- make develop branch with " git checkout -b develop " 
- push files to branch with " git push -u origin develop " 

NOTE: -u is to define (initialize) upstream. Can just use " git push " at next push  