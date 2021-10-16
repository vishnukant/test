git init
git config --global user.name "Vishnukant"
git config --global user.email "vishnukant4u@gmail.com"
git add .
git commit -m 'first commit master'
git checkout -b feature-1
vi index.html
git add index.html
git commit -m 'update feature-1'
git checkout master
git merge feature-1
git remote add origin git@github.com:vishnukant/test.git

ssh-keygen  #generate public private key and on github deplyment key

git push origin master

