FROM openjdk:21-slim

MAINTAINER eazybytes.com

COPY target/accounts-0.0.1-SNAPSHOT.jar account.jar

ENTRYPOINT ["java","-jar","account.jar"]

# Command to run this file : docker build . -t sophakz/accounts-service:s4