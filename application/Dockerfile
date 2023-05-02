FROM openjdk:17-jdk-alpine
ARG JAR_FILE=target/*.jar
COPY ./target/application-0.0.1-SNAPSHOT.jar app.jar
COPY target/*.jar application-0.0.1-SNAPSHOT.jar
ENTRYPOINT ["java", "-jar", "/app.jar"]

