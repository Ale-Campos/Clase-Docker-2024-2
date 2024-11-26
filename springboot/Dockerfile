FROM maven:3.9.9-eclipse-temurin-23-alpine


WORKDIR /app

ADD demo/ .

RUN mvn clean install

EXPOSE 8080

CMD ["java", "-jar", "/app/target/demo-0.0.1-SNAPSHOT.jar"]