FROM openjdk:17
CMD ["./mvnw", "clean", "package"]
ARG JAR_FILE=target/EurekaServer-0.0.1-SNAPSHOT.jar
COPY ${JAR_FILE} app.jar
ENTRYPOINT ["java","-jar","/app.jar"]
