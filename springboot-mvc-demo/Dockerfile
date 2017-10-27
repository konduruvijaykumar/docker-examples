FROM openjdk:8-jre

EXPOSE 8080

ADD ./target/springboot-mvc-demo-0.0.1-SNAPSHOT.jar springmvc.jar

ENTRYPOINT ["java", "-jar", "springmvc.jar"]
