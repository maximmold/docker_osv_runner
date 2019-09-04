FROM openjdk:8-jdk-alpine
VOLUME /tmp
COPY *.jar app.jar
ENTRYPOINT ["java","-verbose:gc", "-XX:+PrintFlagsFinal","-jar","/app.jar"]
