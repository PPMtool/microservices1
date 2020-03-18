FROM openjdk:8
COPY target/currency-exchange-service-0.0.1-SNAPSHOT.jar currency-exchange-service-0.0.1-SNAPSHOT.jar
EXPOSE 8000
ENTRYPOINT [ "java" , "-Xmx512m" , "-jar" , "currency-exchange-service-0.0.1-SNAPSHOT.jar" ]
