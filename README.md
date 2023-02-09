created a new env
conda create -n wineq python=3.7 -y
conda activate wineq

created requirements.txt
installed the requirements
pip install -r requirements.txt


git init

dvc init

dvc add data_given/winequality-red.csv
'''
bash
git add .
'''
git commit-m "first commit"

git add . && git commit -m "update READme.md" 

git remote add origin https://github.com/Viswa243/simple-dvc.git

git branch -M main

git push -u origin main

to update use git add . && git commit -m "update READme.md"  and git push -u origin main

