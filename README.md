# gauravlab01

git clone https://github.com/gauravlab01/gauravlab01.git gauravlab01

cd gauravlab01/

git remote -v #this command to check clonned repository

git init

git add README.md

#run below 2 commands if performing commit for first time on machine
command-1 git config --global user.email "gauravlab01@gmail.com"
command-2 git config --global user.email "gauravlab01"


git commit -m "first commit"

git branch -M main #here you can define default brance to upload newly changed file, you can write master insted of mail

git remote add origin https://github.com/gauravlab01/gauravlab01.git #command to reconfirm that repo is added

git push -u origin main #after this command we must provide user name and auth token

git git push -u origin HEAD:master #if you want to upload newly changed file to master branch then use this command
#syntax - git git push -u origin HEAD:<branch_name>

