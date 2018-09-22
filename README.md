# Portal in AWS Cloud Configuration Files

After creating the cloudformation using portal_cloudformation, execute the following:
1. Run AWS_HOST=<tomcat host> ./post-install-provision
2. ssh $AWS_HOST
3. kshell
4. sh ./get-stuff
5. build portalframework
6. build portal-lib
7. probably rebuild portalframework
8. run mvn dependency:copy-dependencies -f pom-deps.xml -DoutputDirectory=classpath
