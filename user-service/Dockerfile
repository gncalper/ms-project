FROM openjdk:17-alpine

WORKDIR user-server

COPY ./target/*.jar user.jar

CMD ["java", "-jar", "user.jar"]