# Use a lightweight Java runtime
FROM amazoncorretto:21-alpine

# Set working directory
WORKDIR /app

# Copy the jar from target folder
COPY target/*.jar app.jar

# Run the app
ENTRYPOINT ["java", "-jar", "app.jar"]
