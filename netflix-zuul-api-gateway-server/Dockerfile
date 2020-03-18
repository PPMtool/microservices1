FROM openjdk:8
COPY target/netflix-zuul-api-gateway-server-0.0.1-SNAPSHOT.jar netflix-zuul-api-gateway-server-0.0.1-SNAPSHOT.jar
EXPOSE 8765
ENTRYPOINT [ "java" , "-Xmx512m" , "-jar" , "netflix-zuul-api-gateway-server-0.0.1-SNAPSHOT.jar" ]
