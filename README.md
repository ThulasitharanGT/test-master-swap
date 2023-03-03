# test-master-swap


# change the default branch to develop

git clone the repo

git checkout master 
git branch -m bugfix #rename branh
git commit -m "rename master to bugfix"
git push origin bugfix

git checkout develop 
git branch -m master #rename branh
git commit -m "rename develop to master"
git push origin master

git checkout -b develop_1 master 
git branch -m develop #rename branh
git push origin develop


 

