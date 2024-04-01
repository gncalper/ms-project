FROM openjdk:17-alpine

WORKDIR notification-server

COPY ./target/*.jar notification.jar

CMD ["java", "-jar", "notification.jar"]