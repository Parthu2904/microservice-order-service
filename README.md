# microservice-order-service
Create a standalone Order microservice exposing REST endpoints with DTOs and validation.
# 📦 Order Microservice (Spring Boot)

A simple order management REST microservice — production-style layering with DTOs and mapping.

### 🧰 Tech Stack
- Java 17, Spring Boot 3  
- Spring Data JPA  
- ModelMapper for DTO conversion  
- Lombok  

### 💡 Highlights
- DTO pattern  
- Validation with `@Valid`  
- H2 for dev mode  
- Can integrate with Feign clients for PaymentService

### ▶️ Run
```bash
mvn spring-boot:run
