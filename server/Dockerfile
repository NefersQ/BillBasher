FROM ubuntu:latest
LABEL authors="nefer"

ENTRYPOINT ["top", "-b"]
FROM openjdk:17-slim
COPY target/billbasher-0.0.1-SNAPSHOT.jar billbasher.jar
EXPOSE 8080
ENTRYPOINT ["java", "-jar", "billbasher.jar"]