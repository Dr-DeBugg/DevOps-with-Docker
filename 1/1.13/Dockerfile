FROM openjdk:8
COPY . .
WORKDIR /spring-example-project-master
RUN java -version
RUN ["./mvnw", "package"]
CMD ["java", "-jar", "./target/docker-example-1.1.3.jar"]
