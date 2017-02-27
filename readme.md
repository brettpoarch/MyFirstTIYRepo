How to Git:

mkdir MyProject (name whatever you want)
cd MyProject 

git init
touch(create) a file -- readme.md
subl . [put stuff in readme file]

git add . 
git commit -m "initial commit"

create repo on github and grab the ssh link
 - looks like (but isn't) git@github.com:brettpoarch/MyProject.git
   add our remote 
 - git remote add (name) origin git@github.com:brettpoarch/MyProject.git
 git push origin master

 git add .
 git commit -m "my message"
 git push origin master