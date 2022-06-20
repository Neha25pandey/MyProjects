FROM openjdk:8-jdk-alpine
RUN mkdir /opt/myservice

COPY target/08-aws-hello-world-rest-api-pipeline-0.0.1-SNAPSHOT.jar  /opt/myservice/app.jar
WORKDIR /opt/myservice
EXPOSE 8080
CMD java -jar app.jar
#ENTRYPOINT [ "sh", "-c", "java $JAVA_OPTS -Djava.security.egd=file:/dev/./urandom -jar /app.jar" ]
