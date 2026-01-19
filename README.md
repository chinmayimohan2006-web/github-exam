This repository is created for my Gitlab exam and i have got the 3rd experiment
first and foremost we have to create a file and add using git add command 
we commit the changes with the message so that  it will be easy for us to identify the changes 
next will clone remotly with our github repo URL
then we create a branch 
here i have created another branch names feature-branch where the chnages are made and aggain commited
next in 3rd experiment we use STASH wich saves the chnages temporarily that are not commited 
i have added an output file which will show the output of the program that i have committed


the commands i have used are

git init
notepad pgm.py
git add pgm.py
git commit -m "Experiment 1"
git remote add origin <URL>
git pull --rebase origin main
git push -u origin main

git branch
git checkout -b feature-branch
notepad pgm.py
git add pgm.py
git commit -m "Updated to feature-branch"
git status

git checkout main
notpad pgm.py
git status
git stash
git status
git checkout feature-branch
git stash apply 
git status

for output
git checkout main
python pgm.py
python pgm.py > output.txt
notepad output.txt
git add output.txt
git commit -m "Output added"
git push origin main
git push
git commit 

git status
