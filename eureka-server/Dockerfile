FROM openjdk:8
VOLUME /tmp
ADD eureka-server/target/eureka-server-0.0.1-SNAPSHOT.jar app.jar 
EXPOSE 8761
ENTRYPOINT ["java", "-jar", "app.jar"]