FROM openjdk:8-jdk
COPY "./spring-boot-*.jar" "/test-java.jar"
EXPOSE 8080
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/test-java.jar"]

