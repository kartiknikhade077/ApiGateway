# Use OpenJDK 21 base image
FROM openjdk:21-jdk-slim

# Set working directory inside container
WORKDIR /app

# Copy the JAR file into the container
COPY target/ApiGateway-0.0.1-SNAPSHOT.jar app.jar

# Expose the application port
EXPOSE 9090

# Run the JAR
ENTRYPOINT ["java", "-jar", "app.jar"]
