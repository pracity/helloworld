 
1. create new openshift project using below link 
https://developers.openshift.com/servers/tomcat/getting-started.html
2. create new github project using below link 
https://help.github.com/articles/create-a-repo/
3. dont commit any changes to gitub project created in step2 
4. add public key in github. 
4a. public key will be created by default when you careted openshift project at location 
C:\Users\<userid>\.ssh
4b. add this public key in your github repository 
https://github.com/<userid>/<repositoryid>/settings
5. add github repository to your project 
git remote add  github git@github.com:pracity/helloworld.git
6. push changes to individual repository 
	git push -u origin 
this will push changes to openshift
	git push -u github 
this will push changes to github