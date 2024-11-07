FROM openjdk:17-jdk-slim
ARG JAR_FILE=target/videojuegos-0.0.1.jar
COPY ${JAR_FILE} app_videojuegos.jar
EXPOSE 8080
ENTRYPOINT ["java", "-jar", "app_videojuegos.jar"]