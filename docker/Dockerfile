FROM openjdk:17-jdk-alpine
VOLUME /tmp
COPY target/springboot-app.jar app.jar
ENTRYPOINT ["java", "-jar", "/app.jar"]
