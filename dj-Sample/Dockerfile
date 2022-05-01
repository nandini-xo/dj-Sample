FROM openjdk:11
MAINTAINER  Nandini Sharma <nandinisharma1324@gmail.com>
ARG JAR_FILE=target/*.jar
COPY target\dj-Sample-0.0.1-SNAPSHOT.jar dj-Sample.jar
EXPOSE 8080
CMD ["java","-jar","/dj-Sample-0.0.1-SNAPSHOT.jar"]