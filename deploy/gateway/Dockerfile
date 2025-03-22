FROM openjdk:17
WORKDIR /app
COPY MicroserviceGateway-1.0.0.jar gateway.jar
EXPOSE 8888
ENTRYPOINT [ "java","-jar","gateway.jar" ]