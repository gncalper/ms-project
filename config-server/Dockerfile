FROM openjdk:17-alpine

WORKDIR config-server

COPY ./target/*.jar config.jar

CMD ["java", "-jar", "config.jar"]