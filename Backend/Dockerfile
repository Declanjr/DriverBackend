FROM eclipse-temurin:21-jdk-alpine
VOLUME /tmp
COPY Backend/target/*.jar app.jar
ENTRYPOINT [ "java", "-jar", "/app.jar" ]
EXPOSE 8080
