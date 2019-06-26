#WAR on Tomcat
FROM tomcat:8-jdk8
COPY companyNews.war /usr/local/tomcat/webapps/
COPY prevayler-core-2.6.jar /usr/local/tomcat/webapps/
CMD ["catalina.sh", "run"]
