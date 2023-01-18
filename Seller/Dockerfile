FROM openjdk:8
EXPOSE 9001
ADD target/seller-docker.jar seller-docker.jar
ENTRYPOINT ["java","-jar","/seller-docker.jar"]