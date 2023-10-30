FROM openjdk:20-slim
LABEL authors="inkerinmaa"
# The application's jar file
ARG JAR_FILE

# Add the application's jar to the container
COPY ${JAR_FILE} app.jar

#execute the application
ENTRYPOINT ["java", "-jar", "/app.jar"]