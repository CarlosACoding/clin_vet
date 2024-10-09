FROM openjdk:21-jdk-slim
ARG JAR_FILE=target/ComercioWeb-0.0.1-SNAPSHOT.war
COPY ${JAR_FILE} ComercioWeb.war
EXPOSE 8080
ENTRYPOINT ["java", "-jar", "ComercioWeb.war"]