FROM openjdk:17
CMD ["./mvnw", "clean", "package"]
VOLUME /tmp
ARG JAR_FILE=target/PagingJoin-0.0.1-SNAPSHOT.jar
COPY ${JAR_FILE} app.jar
EXPOSE 8082
ENTRYPOINT ["java","-jar","/app.jar"]

