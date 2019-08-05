FROM openjdk:11.0.3
ADD ./target/service-0.0.1-SNAPSHOT.jar service-0.0.1-SNAPSHOT.jar
EXPOSE 8761
ENTRYPOINT ["java", "-jar", "service-0.0.1-SNAPSHOT.jar"]