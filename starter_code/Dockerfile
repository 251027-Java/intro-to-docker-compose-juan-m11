# TODO: Select Base Image
FROM eclipse-temurin:17-jre-alpine

WORKDIR /app

# TODO: Copy JAR file
COPY target/*.jar app.jar

EXPOSE 8080

# TODO: Set Entrypoint
ENTRYPOINT ["java", "-jar", "app.jar"]