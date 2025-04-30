# Use an OpenJDK base image
FROM openjdk:17-jdk-alpine

# Set the working directory inside the container
WORKDIR /app

# Copy the Java source code into the container
COPY src/Main.java /app/Main.java

# Compile the Java source code
RUN javac Main.java

# Run the compiled Java program
CMD ["java", "Main"]
