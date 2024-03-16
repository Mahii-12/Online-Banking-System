# Technology Stack:

## Java, Maven, Spring Boot, Hibernate: 
* I chose Java as the programming language due to its robustness and widespread usage. Spring Boot simplifies the setup of Spring-based applications, while Hibernate facilitates object-relational mapping (ORM) for  streamlining database interactions and Spring Security with JWT authentication and authorization mechanisms.

## MySQL Database:
* Utilized MySQL database to store user, account, and transaction data. MySQL offers robust relational database management capabilities, ensuring efficient data storage and retrieval.

## Scalability and SOLID Principles:

* SOLID Principles:
> Adhered to SOLID principles (Single Responsibility, Open/Closed, Liskov Substitution, Interface Segregation, Dependency Inversion) to design a modular, maintainable, and extensible system. Ensured scalability and future enhancements by following best practices in system design and architecture.

## Spring Security with JWT Authentication:
* Implemented Spring Security to regulate access to different endpoints securely. Utilized JWT (JSON Web Token) authentication mechanism to authenticate and authorize users, ensuring secure access to the system's functionalities.

## CRUD Operations:
* Implemented CRUD (Create, Read, Update, Delete) operations for managing users, their accounts and users transactions effectively. Ensured seamless handling of user and account data manipulation for enhanced user experience.

## Transaction Service:
* Developed a TransactionService class to facilitate transactions for users and their accounts. Implemented transactional operations such as Deposit, Withdrawal, and Transfer to enable seamless fund management.

## Authorization Endpoints:
* Configured authorization endpoints to permit all REST endpoints. This allowed users convenient access to system functionalities without authentication barriers.
> Endpoints:
 ```json
{
    "/users/**" : "Permit All User related endpoints",
    "/account/**" : "Permit All User Account related endpoints",
    "/transaction/**" : "Permit All User Transaction endpoints"
}
  ```

## Testing and Validation:
* Utilized Postman for comprehensive testing and validation of REST endpoints. Conducted functional testing to ensure correct behavior and adherence to specified requirements, enhancing system reliability.
