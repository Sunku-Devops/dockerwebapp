FROM tomcat:8-jre11

RUN rm -rf /usr/local/tomcat/webapps/*

COPY /home/ec2-user/Jenkins/workspace/DockerDeploy/target/vprofile-v2.war /usr/local/tomcat/webapps/ROOT.war

CMD ["catalina.sh", "run"]

#this is a comment 1
