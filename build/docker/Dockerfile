FROM amazoncorretto:17.0.7-alpine
CMD ["./gradlew", "clean", "build"]
ARG JAR_FILE_PATH=*.jar
COPY ${JAR_FILE_PATH} app.jar
EXPOSE 8081
ENTRYPOINT ["java", "-jar", "app.jar"]