## **SpringBoot**

### @SpringBootApplication

The @SpringBootApplication annotation is used to mark the main class of a Spring Boot application. This annotation combines three other annotations:

#### @Configuration:
is used to mark classes that define bean configurations for the application context.

#### @EnableAutoConfiguration:

analyzes the dependencies in the classpath and automatically configures beans

#### @ComponentScan:

Tells Spring to scan the current package and its sub-packages for components, services, and configurations.

### @Bean

used to declare a method as a producer of a bean managed by the Spring IoC container. When you annotate a method with @Bean, Spring will execute that method to create an instance of the bean and register it with the container.

### @Component

is a generic stereotype annotation used to designate a class as a Spring-managed component. It indicates that a class is a candidate for auto-detection and instantiation by the Spring IoC container.

### @Service

used to mark a class as a service component in the Spring application context. It is a specialization of the @Component annotation and is typically used to annotate classes that contain business logic, perform operations, or coordinate tasks within the application.

### @RestController

is a specialized version of the @Controller annotation. It's typically used to create RESTful web services in Spring applications.

### @GetMapping

to map HTTP GET requests to specific handler methods in controller classes. It's part of Spring's support for building RESTful web services and is typically used in conjunction with the @RestController or @Controller annotations.

### @JsonIgnoreProperties

used in Spring applications to instruct the Jackson JSON library to ignore specific properties during serialization and deserialization of JSON objects.

### @JsonProperty

to specify the name of a property during serialization and deserialization of JSON objects. 