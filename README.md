# spring-boot-mongodb
This repository contains a Spring Boot example project for MongoDB.

For a code review of this repo, see my related [blog post](https://springframework.guru/3402-2/).

You can learn more about my courses [here](http://courses.springframework.guru/courses/) on my site.

Two to execute the project:

1) From the command prompt: 
   > java -Dspring.data.mongodb.uri=mongodb://192.168.99.100:27017/product -jar target/spring-boot-mongodb-0.0.1-SNAPSHOT.jar

2) From the editor i.e. either Spring STS or intellij:
  > application.properties:
        spring.data.mongodb.uri=mongodb://192.168.99.100:27017/test
  > run the SpringBootMongodbApplication      
