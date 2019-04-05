FROM tomcat:7.0

COPY petclinic.war /usr/local/tomcat/webapps/petclinic.war
COPY data-access.properties /usr/local/tomcat/webapps/petclinic/WEB-INF/classes/spring/data-access.properties
COPY mysql-connector-java-5.1.34-bin.jar  /usr/local/tomcat/webapps/petclinic/WEB-INF/lib/mysql-connector.jar
COPY tomcat-users.xml /usr/local/tomcat/conf/tomcat-users.xml

CMD ["/usr/local/tomcat/bin/catalina.sh", "run"]