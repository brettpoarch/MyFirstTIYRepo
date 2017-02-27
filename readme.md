How to Git:

1. mkdir MyProject (name whatever you want)
2. cd MyProject 

3. git init
4. touch(create) a file -- readme.md
5. subl . [put stuff in readme file]

6. git add . 
7. git commit -m "initial commit"

8. create repo on github and grab the ssh link
 - looks like (but isn't) git@github.com:brettpoarch/MyProject.git
   add our remote 
 - git remote add (name) origin git@github.com:brettpoarch/MyProject.git
 
 9. git push origin master

 10. git add .
 11. git commit -m "my message"
 12. git push origin master