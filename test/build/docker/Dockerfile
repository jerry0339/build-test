FROM openjdk:17
# CMD ["./gradlew", "clean", "build"]
COPY ./member-service-1.0.0-SNAPSHOT.jar /usr/src/myapp/member-service-1.0.0.jar
ENTRYPOINT ["java", "-jar", "/usr/src/myapp/member-service-1.0.0.jar"]
# ENTRYPOINT ["java", "-Dspring.profiles.active=${spring_profiles_active}", "-Dapplication.role=${application_role}", "-Dpostgresql.filepath=${postgresql_filepath}", "-jar", "/usr/src/myapp/member-service-1.0.0.jar"]
EXPOSE 8081
WORKDIR /usr/src/myapp