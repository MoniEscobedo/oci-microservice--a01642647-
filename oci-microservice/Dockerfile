FROM openjdk:17-jdk-slim
WORKDIR /oci-microservice-a00354829
COPY /target/*.jar oci-microservice-a00354829.jar
COPY /src/main/resources/Wallet_javadev101 /oci-microservice-a00354829/Wallet_javadev101
ENV TNS_ADMIN=/oci-microservice-a00354829/Wallet_javadev101
EXPOSE 8080
ENTRYPOINT [ "java", "-jar", "oci-microservice-a00354829.jar" ]