FROM java:8u111-jre-alpine
MAINTAINER vaneetkataria54@gmail.com
COPY target/spring-cloud-config-server-0.0.1-SNAPSHOT.jar /App.jar
EXPOSE 8300
VOLUME /tmp
ENTRYPOINT ["java", "-jar" ,  "/App.jar"]

