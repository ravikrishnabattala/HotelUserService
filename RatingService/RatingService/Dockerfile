FROM openjdk:17-jdk-slim

EXPOSE 8083

ADD target/RatingService-0.0.1-SNAPSHOT.jar RatingService-0.0.1-SNAPSHOT.jar

ENTRYPOINT ["java", "-jar","RatingService-0.0.1-SNAPSHOT.jar"]