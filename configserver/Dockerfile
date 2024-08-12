FROM openjdk:17
WORKDIR /app
COPY ./target/configserver-0.0.1-SNAPSHOT.jar /app/configserver.jar
EXPOSE 8888
CMD ["java", "-jar", "configserver.jar"]