FROM openjdk:11

MAINTAINER "Ashok & Raj"

COPY target/spring-boot-docker-app.jar  /usr/app/

WORKDIR /usr/app/

EXPOSE 8081

ENTRYPOINT ["java", "-jar", "spring-boot-docker-app.jar"]
