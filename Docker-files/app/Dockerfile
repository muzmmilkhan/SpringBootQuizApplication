FROM openjdk:15.0.2
EXPOSE 8080
RUN curl -v -u admin:admin123 -o demo-0.0.1-SNAPSHOT.jar http://18.119.109.156:8081/repository/vprofile-release/QA/vproapp/9-23-01-26_20:36/vproapp-9-23-01-26_20:36.jar
ENTRYPOINT ["java", "-jar", "/demo-0.0.1-SNAPSHOT.jar"]
