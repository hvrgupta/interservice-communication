# 🧩 Spring Boot Microservices Communication

This project demonstrates **five different HTTP communication methods** between two Spring Boot microservices:

- **`provider`** – exposes a simple REST API.
- **`consumer`** – consumes the provider's API using 5 different clients.


## 🔗 Communication Methods Implemented

| Method           | Description                                                                 |
|------------------|-----------------------------------------------------------------------------|
| **RestTemplate** | Traditional blocking HTTP client for REST calls.                           |
| **RestClient**   | Newer, lightweight client introduced in Spring 6 (replacement for RestTemplate). |
| **WebClient**    | Reactive, non-blocking HTTP client from Spring WebFlux.                    |
| **Http Interface** | Declarative interface-based client in Spring 6 using annotations.         |
| **OpenFeign**    | Declarative REST client from Spring Cloud OpenFeign.                      |

Each of these methods is implemented in the `consumer` application to call an API exposed by the `provider`.

### ✅ Prerequisites

- Java 17+
- Maven 3.8+
- Spring Boot 3.x
- Spring Framework 6.x
- Spring Cloud OpenFeign (for Feign client)
