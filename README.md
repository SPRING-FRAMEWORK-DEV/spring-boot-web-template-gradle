# spring-boot-web-template-gradle
spring-boot-web-template-gradle<br/>
step1:<br/>

run the command in cmd:  build.bat <br/>
if build successful you will find a folder build/libs/ <br/>
go to build/libs/ and open a cmd there<br/>
You will find a jar or war file.<br/>
Now execute command: java -jar your_jar_war_file_name<br/>

<br/>
step2:
<br/>
Now the application will run on the port 8080. You can access in your browser using localhost:8080<br/>
If application failed to start at 8080 then change the port to a different value in src/main/resources/application.properties file with<br/>
server.port=9898<br/>

Now continue again from step1 and your application will be accessible at localhost:9898

