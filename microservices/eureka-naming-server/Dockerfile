FROM openjdk:8-jdk-alpine
VOLUME /tmp
EXPOSE 8761
ADD *.jar app.jar
ENTRYPOINT ["sh", "-c", "java -jar /app.jar"]
