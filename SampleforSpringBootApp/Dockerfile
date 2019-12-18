FROM openjdk:8
ADD ./target/app-service.jar app-service.jar 
EXPOSE 8280
ENTRYPOINT ["java", "-jar", "app-service.jar"]