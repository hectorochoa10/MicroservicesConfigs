FROM openjdk:17
WORKDIR /app
COPY MicroserviceConfig-1.0.0.jar config.jar
EXPOSE 7777
ENTRYPOINT [ "java","-jar","config.jar" ]