FROM adoptopenjdk/openjdk11:alpine-jre
ADD http://43.204.218.212:8081/repository/abhishek/ /app/*.jar
EXPOSE 8080
ENTRYPOINT ["java","-jar","/app/*.jar"]
