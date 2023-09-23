# Use an official Java runtime as a parent image
FROM openjdk:11-jre-slim

# Set the working directory inside the container
WORKDIR /app

# Copy the WAR file into the container at the specified directory
COPY your-app.war /app/

# Expose the port your application will run on
EXPOSE 8081

# Specify the command to run your application
CMD ["java", "-jar", "basketball-1.0-SNAPSHOT.jar"]
