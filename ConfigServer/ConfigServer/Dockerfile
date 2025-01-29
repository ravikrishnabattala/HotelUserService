FROM openjdk:17-jdk-slim

EXPOSE 8085

ADD target/ConfigServer-0.0.1-SNAPSHOT.jar ConfigServer-0.0.1-SNAPSHOT.jar

ENTRYPOINT ["java", "-jar","ConfigServer-0.0.1-SNAPSHOT.jar"]