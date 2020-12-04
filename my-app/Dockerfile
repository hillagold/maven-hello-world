FROM maven:3.6.3-jdk-8-alpine
# copy application WAR (with libraries inside)
WORKDIR /app
COPY . .
ENTRYPOINT ["java", "-cp", "target/my-app-1.0-SNAPSHOT.jar", "com.mycompany.app.App"]
