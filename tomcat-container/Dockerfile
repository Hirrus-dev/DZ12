FROM tomcat:8.5-alpine
RUN rm -rf /usr/local/tomcat/webapps/*
ADD ./App42PaaS-Java-MySQL-Sample-0.0.1-SNAPSHOT.war /usr/local/tomcat/webapps/ROOT.war
ADD ./Config.properties /usr/local/tomcat/ROOT/
EXPOSE 8080