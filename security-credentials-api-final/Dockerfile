FROM openjdk:8-jre

EXPOSE 8080

ADD ./target/security-credentials-api-final-0.0.1-SNAPSHOT.jar springrest.jar

ENTRYPOINT ["java", "-jar", "springrest.jar"]
