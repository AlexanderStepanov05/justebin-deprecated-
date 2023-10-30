FROM amazoncorretto:20
LABEL authors="inkerinmaa"

# Add the application's jar to the container
COPY build/libs/auth-service-0.0.1-SNAPSHOT.jar /app.jar

#execute the application
ENTRYPOINT ["java", "-jar", "/app.jar"]