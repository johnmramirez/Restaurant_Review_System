FROM openjdk:17

VOLUME /tmp

EXPOSE 8081

ARG JAR_FILE=build/libs/project2b-1.0.0.jar

ADD ${JAR_FILE} app.jar

ENTRYPOINT ["java","-jar","/app.jar"]