FROM eclipse-temurin:17-jre-alpine

WORKDIR /app

COPY app/target/sample-java-maven-app.jar /app/sample-java-maven-app.jar

EXPOSE 8080

ENTRYPOINT ["java", "-jar", "/app/sample-java-maven-app.jar"]