FROM maven:alpine
USER root
RUN apk add nano && apk add git &&\
    git clone https://github.com/Hirrus-dev/App42PaaS-Java-MySQL-Sample
WORKDIR /App42PaaS-Java-MySQL-Sample
RUN mvn package && cp ./target/*.war /opt && cp ./WebContent/Config.properties /opt
CMD ls -al