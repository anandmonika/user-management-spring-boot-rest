# User Management Application REST API 
### Spring Boot + Hibernate + MySQL

## Description
This Project shows the list of Users which are stored in the MySQL Database. Using the following endpoints, different operations can be achieved

### REST API Structure

| API Name  | HTTP Method | Path | Status Code | Description |
|---|---|---|---|---|
| GET Users | GET | `/api/v1/users` | 200 (OK) | All user resources are fetched |
| POST Users | POST  | `/api/v1/users`  | 201 (Created)  | A new User resource is created |
|  GET User |  GET  | `api/v1/users/{id}`  | 200 (OK)  | One User resource is fetched |
| PUT User  | PUT  |  `api/v1/users/{id}` | 200 (OK)  | User resource is updated  |
| DELETE User | DELETE | `api/v1/users/{id}` | 204 (No Content) | User resource is deleted |

## Libraries Used
- Spring Boot
- Spring Framework
- Hibernate
- Maven
- Spring Data JPA
- MYSQL

## Tools Used
- IDE - Eclipse
- Git
- Postman - For api testing

## Compilation Command
- `maven clean install`
