FROM NEW
mkdir <dirname>
git init  -  for new projects
create files
git add .  -  stage all files
git commit -m "message"
create repository on github
git remote add origin <repo URL>
git push origin master

FROM EXISTING
git add .
git commit -m ""
git push origin master

