FROM openjdk:8-jre-alpine

WORKDIR /app

COPY target/service-discovery-0.0.1-SNAPSHOT.jar .

EXPOSE 8761

CMD ["java", "-jar", "service-discovery-0.0.1-SNAPSHOT.jar"]
