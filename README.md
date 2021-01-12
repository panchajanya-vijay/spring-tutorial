# spring-tutorial

Micro Service: Micro Service is an architecture that allows the developers to develop and deploy services independently. Each service running has its own process and this achieves the lightweight model to support business applications.

Spring Boot: To develop a stand-alone and productoin-grade application that can just run.

@EnableAutoConfiguration annotation: Spring Boot automatically configures your application based on the dependencies you have added to the project. 
@SpringBootApplication annotation: The entry point of the spring boot application is the class contains and the main method. 
@ComponentScan annotation: Spring Boot automatically scans all the components included in the project by using.

Spring Boot Starters
Examples:
Spring Boot Starter Actuator dependency
<dependency>
   <groupId>org.springframework.boot</groupId>
   <artifactId>spring-boot-starter-actuator</artifactId>
</dependency>

Spring Boot Starter Security dependency is used for Spring Security. Its code is shown below −
<dependency>
   <groupId>org.springframework.boot</groupId>
   <artifactId>spring-boot-starter-security</artifactId>
</dependency>

Spring Boot Starter web dependency is used to write a Rest Endpoints. Its code is shown below −
<dependency>
   <groupId>org.springframework.boot</groupId>
   <artifactId>spring-boot-starter-web</artifactId>
</dependency>

Spring Boot Starter Thyme Leaf dependency is used to create a web application. Its code is shown below −
<dependency>
   <groupId>org.springframework.boot</groupId>
   <artifactId>spring-boot-starter-thymeleaf</artifactId>
</dependency>
Spring Boot Starter Test dependency is used for writing Test cases. Its code is shown below −

<dependency>
   <groupId>org.springframework.boot</groupId>
   <artifactId>spring-boot-starter-test</artifactId>
</dependency>

Java Code
import org.springframework.boot.SpringApplication;
import org.springframework.boot.autoconfigure.EnableAutoConfiguration;

@EnableAutoConfiguration
public class DemoApplication {
   public static void main(String[] args) {
      SpringApplication.run(DemoApplication.class, args);
   }
}
