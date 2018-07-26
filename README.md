# Spring Eureka Server - Service Discovery
Netflix Eureka Server setup as Service Discovery using Spring Boot framework

## application.yml
```yml
spring:
  application:
    name: Eureka-Server
server:
  port: 8761

eureka:
  client:
    registerWithEureka: true
    fetchRegistry: true
    serviceUrl:
      defaultZone: http://localhost:8761/eureka/
```
