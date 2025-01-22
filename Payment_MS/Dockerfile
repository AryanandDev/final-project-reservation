# Step 1: Use a base image with OpenJDK
FROM openjdk:17

# Step 2: Set the working directory
WORKDIR /app

# Step 3: Copy your Spring Boot JAR file into the container
COPY target/Payment_MS-0.0.1-SNAPSHOT.jar app.jar

# Step 4: Expose the port the app will run on
EXPOSE 8084

# Step 5: Run the Spring Boot app
ENTRYPOINT ["java", "-jar", "app.jar"]