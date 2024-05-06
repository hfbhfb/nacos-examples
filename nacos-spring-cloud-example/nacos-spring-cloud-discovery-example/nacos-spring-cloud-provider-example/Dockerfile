# FROM openjdk:8-jdk-alpine
FROM openjdk:11-jdk-oraclelinux7
WORKDIR /app
COPY target/nacos-spring-cloud-provider-example-0.2.0-SNAPSHOT.jar nacos-spring-cloud-provider-example-0.2.0-SNAPSHOT.jar
CMD ["java","-Xmx1024m","-jar", "nacos-spring-cloud-provider-example-0.2.0-SNAPSHOT.jar"]
