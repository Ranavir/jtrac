step 1 - extract the jtrac.war to jtrac
step 2 - open WEB-INF\classes\jtrac-init.properties give the folder path of uncomment the path jtrac.home let say path is C:/jtrac
step 3 - copy the build of extracted jtrac now and put in tomcat webapp
step 4 - start tomcat
step 5 - check file jtrac.properties inside C:/jtrac
step 6 - stop tomcat
optional- (if you want to change database)
step 7 - create a database with name jtrac in your database
step 8 - put your jdbc jar of the database inside lib folder of your build in tomcat
step 9 - change the configuration in jtrac.properties as per you database
step 10 - restart tomcat
Note  :- now all the related tables auto created inside your db and now you can login for first time with uname- admin password - admin
Ref:-
http://www.programering.com/a/MjM5kTMwATc.html