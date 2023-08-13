FROM adoptopenjdk/openjdk11:alpine-jre
ADD http://43.204.218.212:8081/repository/abhishek/ /app/spring-boot-web.jar
EXPOSE 8080
ENTRYPOINT ["java","-jar","/app/spring-boot-web.jar"]
