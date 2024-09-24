# RSE School

##Clone fork

git clone https://github.com/steffengraber/school
cd nest-simulator
git remote add upstream https://github.com/steffengraber/school.git

## Update fork

git checkout master 
git fetch upstream 
git merge upstream/master --ff-only 
git push origin master 

