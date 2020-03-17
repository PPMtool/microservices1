 
FROM openjdk:8
COPY target/currency-conversion-service-0.0.1-SNAPSHOT.jar  currency-conversion-service-0.0.1-SNAPSHOT.jar
EXPOSE 8100
ENTRYPOINT [ "java" , "-Xmx512m" , "-jar" , "currency-conversion-service-0.0.1-SNAPSHOT.jar"]
