FROM tomcat:9.0.48-jdk8-openjdk

COPY ./webProject/target/webProject.war /usr/local/tomcat/webapps

EXPOSE 8080

CMD ["catalina.sh","run"]