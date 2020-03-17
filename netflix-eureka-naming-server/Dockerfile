FROM openjdk:8
COPY target/netflix-eureka-naming-server-0.0.1-SNAPSHOT.jar  netflix-eureka-naming-server-0.0.1-SNAPSHOT.jar
EXPOSE 8761
ENTRYPOINT [ "java" , "-Xmx512m" , "-jar" , "netflix-eureka-naming-server-0.0.1-SNAPSHOT.jar" ]

