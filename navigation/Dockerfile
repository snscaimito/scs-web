FROM openjdk:jdk-alpine
MAINTAINER sns@caimito.net

COPY target/navigation*.jar /opt/app.jar

EXPOSE 8081

ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/opt/app.jar"]