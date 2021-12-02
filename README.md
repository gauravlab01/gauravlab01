# gauravlab01

git clone https://github.com/gauravlab01/gauravlab01.git gauravlab01

cd gauravlab01/

git remote -v #this command to check clonned repository

git init

git add README.md

git commit -m "first commit"

git branch -M main

git remote add origin https://github.com/gauravlab01/gauravlab01.git #command to reconfirm that repo is added

git push -u origin main #after this command we must provide user name and auth token

git git push -u origin HEAD:master #if you want to upload newly changed file to master branch then use this command
#syntax - git git push -u origin HEAD:<branch_name>
