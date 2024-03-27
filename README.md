Devops Project

in terminal i did the following
    mvn clean install

I downloaded toncat and navigated to the Tomcat/bin folder
I ran the following command
    ./startup.sh && tail -f ../logs/catalina.out
    check on browser localhost:8080, tomcat should be up and running.

Then from the maven project, copy the webapp.war file from target folder and place inside the tomcat/webapps/ folder 
    check on the browser localhost:8080/webapps , the app should be up and running

    