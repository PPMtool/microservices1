FROM openjdk:8
COPY target/netflix-zuul-api-gateway-server-0.0.1-SNAPSHOT.jar netflix-zuul-api-gateway-server-0.0.1-SNAPSHOT.jar
EXPOSE 8765
ENTRYPOINT [ "java" , "-jar" ,  "Xms256m","-Xmx256m" "netflix-zuul-api-gateway-server-0.0.1-SNAPSHOT.jar"]
