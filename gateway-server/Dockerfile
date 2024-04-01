FROM openjdk:17-alpine

WORKDIR gateway-server

COPY ./target/*.jar gateway.jar

CMD ["java", "-jar", "gateway.jar"]