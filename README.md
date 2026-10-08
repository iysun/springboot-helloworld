# springboot-helloworld

A minimal Hello World application built with **Spring Boot 2.7.18** and **Java 8**.

## Endpoints

| Method | Path     | Response              |
|--------|----------|-----------------------|
| GET    | `/`      | `Hello, World!`       |
| GET    | `/hello` | `Hello, Spring Boot!` |

## Requirements

- JDK 8+
- Maven 3.6+

## Run locally

```sh
mvn spring-boot:run
```

Then open <http://localhost:8080/> or <http://localhost:8080/hello>.

## Build a runnable jar

```sh
mvn clean package
java -jar target/springboot-helloworld-0.0.1-SNAPSHOT.jar
```

## Test

```sh
curl http://localhost:8080/
# Hello, World!

curl http://localhost:8080/hello
# Hello, Spring Boot!
```
