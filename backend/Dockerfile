FROM maven AS stage1
WORKDIR /app
COPY . .
RUN mvn clean package
RUN mv /app/target/*.jar /app/target/App.jar

FROM openjdk:17-jdk-slim
WORKDIR /build
COPY --from=stage1 /app/target/App.jar .
CMD ["java" ,"-jar","App.jar"]
EXPOSE 8080
