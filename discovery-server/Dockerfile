FROM openjdk:17-alpine

WORKDIR discovwry-server

COPY ./target/*.jar discovery.jar

CMD ["java", "-jar", "discovery.jar"]