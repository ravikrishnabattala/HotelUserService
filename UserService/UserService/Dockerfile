FROM openjdk:17-jdk-slim

EXPOSE 8081

ADD target/UserService-0.0.1-SNAPSHOT.jar UserService-0.0.1-SNAPSHOT.jar

ENTRYPOINT ["java", "-jar","UserService-0.0.1-SNAPSHOT.jar"]