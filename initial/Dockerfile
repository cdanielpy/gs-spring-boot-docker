FROM openjdk:17-jdk
#RUN addgroup --system spring && adduser --system spring -ingroup spring
#RUN addgroup -g spring spring
#RUN adduser -u spring -g spring
#USER spring:spring
ARG JAR_FILE=./target/spring-boot-docker-initial-0.0.1-SNAPSHOT.jar
COPY ${JAR_FILE} app.jar
ENTRYPOINT ["java","-jar","/app.jar"]