FROM openjdk:8
COPY target/netflix-zuul-api-gateway-server-0.0.1-SNAPSHOT.jar /app/netflix-zuul-api-gateway-server-0.0.1-SNAPSHOT.jar
EXPOSE 8765
COPY startup.sh startup.sh
ENTRYPOINT [ "bash","startup.sh"]
