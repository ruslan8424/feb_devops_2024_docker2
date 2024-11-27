FROM openjdk
COPY petclinic-app-code /spring-petclinic
WORKDIR /spring-petclinic 
RUN ./mvnw package 
CMD ["java", "-jar", "target/*.jar"]
 
