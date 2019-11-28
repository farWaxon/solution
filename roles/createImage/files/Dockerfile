FROM java:8-jdk-alpine

COPY jhttp-1.0-SNAPSHOT.jar /usr/app/

WORKDIR /usr/app

EXPOSE 8888

ENTRYPOINT ["java", "-jar", "jhttp-1.0-SNAPSHOT.jar"]
