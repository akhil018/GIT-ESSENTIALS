# GIT-ESSENTIALS
Git commands used everyday will be available here
Add/Push existing project to git

git init

git add .

git commit -m "Initial commit"

git remote add origin <project url>

git remote set-url origin git@github.com:{user_id}/{project_name}.git
  
git push -f origin master
  
The -f option on git push forces the push. If you don't use it, you'll see an error like this:
