FROM openjdk:17
WORKDIR /app
COPY ./target/attendance-service-0.0.1-SNAPSHOT.jar /app/attendance-service.jar
EXPOSE 8085
CMD ["java", "-jar", "attendance-service.jar"]