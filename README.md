Food Fiesta — Spring Boot Full-Stack Dining Management App

Built a full-stack dining management app using Spring Boot 3.4.2 (Java 21), following a layered Controller → Service → Repository → Entity architecture with Spring Data JPA.
Implemented role-based authentication for admin and customer users, with session-managed admin login and Spring Security (BCrypt password encoding).
Integrated Google OAuth2 login as an alternative to traditional credential-based authentication.
Built CRUD modules for user management and product/inventory catalog, rendered via server-side Thymeleaf views.
Documented endpoints with Swagger/OpenAPI, and set up Docker containerization with a GitHub Actions CI pipeline; configured to run on both H2 (dev) and PostgreSQL (prod-style) databases.

Tech Stack: Java 21, Spring Boot, Spring Data JPA, Spring Security, OAuth2, Thymeleaf, PostgreSQL, Docker, GitHub Actions
