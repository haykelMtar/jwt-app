# Spring Boot JWT


## Installation
1. Clone the project `git clone https://github.com/haykelMtar/jwt-app.git`
2. Install dependencies 

## Api doc
run project and enter url http://localhost:8090/swagger-ui.html#/

# Stack

![](https://img.shields.io/badge/java_8-✓-blue.svg)
![](https://img.shields.io/badge/spring_boot-✓-blue.svg)
![](https://img.shields.io/badge/mysql-✓-blue.svg)
![](https://img.shields.io/badge/jwt-✓-blue.svg)
![](https://img.shields.io/badge/swagger_2-✓-blue.svg)

You can find a related post for this repository [here](https://medium.com/@xoor/jwt-authentication-service-44658409e12c).


# project structure

```
spring-boot-jwt/
 │
 ├── src/main/java/
 │   └── com.dev
 │       ├── configuration
 │       │   └── SwaggerConfig.java
 │       │
 │       ├── controller
 │       │   └── UserController.java
 │       │
 │       ├── dto
 │       │   ├── UserDataDTO.java
 │       │   └── UserResponseDTO.java
 │       │   └── TokenUserResponseDTO.java
 │       │   └── UserLoginDTO.java
 │       │
 │       ├── exception
 │       │   ├── CustomException.java
 │       │   └── GlobalExceptionController.java
 │       │
 │       ├── model
 │       │   ├── Role.java
 │       │   └── User.java
 │       │
 │       ├── repository
 │       │   └── UserRepository.java
 │       │
 │       ├── security
 │       │   ├── JwtTokenFilter.java
 │       │   ├── JwtTokenFilterConfigurer.java
 │       │   ├── JwtTokenProvider.java
 │       │   ├── MyUserDetails.java
 │       │   └── WebSecurityConfig.java
 │       │
 │       ├── service
 │       │   └── UserService.java
 │       │
 │       └── JwtAuthServiceApp.java
 │
 ├── src/main/resources/
 │   └── application.properties
 │
 ├── .gitignore
 ├── LICENSE
 ├── mvnw/mvnw.cmd
 ├── README.md
 └── pom.xml

