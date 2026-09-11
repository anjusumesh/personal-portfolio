# Portfolio Projects

This portfolio includes three sample projects designed to demonstrate full-stack Java experience, modern backend development with NestJS, REST API design, database integration, security, testing, CI/CD, and cloud-ready architecture.

---

## 1. Employee Management & HR Portal

**Technology:** Java 21, Spring Boot, Spring Security, JPA/Hibernate, MySQL, HTML, CSS, REST APIs, Docker, Git, Azure DevOps

### Overview

A full-stack HR management application for managing employees, departments, roles, leave requests, and basic employee-related workflows.

### Key Features

- Employee registration and profile management
- Department and role management
- Employee search and filtering
- Leave request and approval workflow
- Role-based access control
- REST APIs for employee and HR operations
- HTML/CSS-based responsive UI
- Server-side validation and centralized exception handling
- Pagination, sorting, and filtering
- Audit information for important operations

### Backend

- Developed RESTful APIs using **Spring Boot**
- Implemented business logic using service-layer architecture
- Used **Spring Data JPA/Hibernate** for database access
- Designed relational entities and relationships in **MySQL**
- Implemented authentication and authorization using **Spring Security**
- Added global exception handling and request validation
- Used DTOs to separate API models from persistence entities

### Frontend

- Developed the UI using **HTML and CSS**
- Created reusable HTML components and structured page layouts
- Integrated frontend forms with Spring Boot REST APIs
- Implemented form validation and error handling
- Added search, filtering, pagination, and role-based UI behavior

### Engineering Highlights

- Layered architecture: Controller → Service → Repository
- REST API documentation using OpenAPI/Swagger
- Unit and integration testing
- Dockerized application for consistent local environments
- CI/CD pipeline for build, test, and deployment

### Portfolio Value

This project demonstrates practical experience in **Java, Spring Boot, HTML, CSS, REST APIs, relational databases, security, and full-stack application development**.

---

## 2. E-Commerce Order Management Platform

**Technology:** Java 21, Spring Boot, Spring Security, JPA/Hibernate, PostgreSQL, HTML, CSS, Redis, Docker, REST APIs, Git, Azure DevOps

### Overview

A scalable e-commerce platform that allows customers to browse products, manage their shopping cart, place orders, and track order status.

The project focuses on backend business logic, transaction management, authentication, and reliable order processing.

### Key Features

- User registration and login
- Product catalog management
- Product search and filtering
- Shopping cart management
- Order creation and order tracking
- Inventory management
- Order status workflow
- Admin product and inventory management
- Role-based authorization
- Centralized error handling
- API validation and pagination

### Backend

- Developed REST APIs using **Spring Boot**
- Implemented authentication and authorization with **Spring Security**
- Used **JPA/Hibernate** for persistence
- Designed PostgreSQL database schema for users, products, inventory, carts, and orders
- Implemented transactional order processing
- Added validation using Jakarta Bean Validation
- Implemented centralized exception handling
- Used Redis for selected caching use cases
- Designed APIs with scalability and maintainability in mind

### Frontend

- Developed the web interface using **HTML and CSS**
- Created reusable product, cart, checkout, and order page components
- Integrated frontend forms and pages with Spring Boot REST APIs
- Implemented role-based navigation and access behavior
- Added client-side validation and user-friendly error handling

### Engineering Highlights

- Transaction management for order creation and inventory updates
- Optimized database queries and API response times
- Added unit and integration tests
- API documentation with Swagger/OpenAPI
- Docker-based local development environment
- CI/CD pipeline using Azure DevOps
- Structured logging and application monitoring

### Example API Areas

```text
GET    /api/products
GET    /api/products/{id}
POST   /api/cart/items
POST   /api/orders
GET    /api/orders/{id}
PATCH  /api/orders/{id}/status
```

### Portfolio Value

This project demonstrates **enterprise Java development, Spring Boot, HTML, CSS, database design, security, transactions, caching, REST APIs, testing, and CI/CD**.

---

## 3. Identity Verification & Border Security API

**Technology:** NestJS, TypeScript, Node.js, MongoDB, REST APIs, HTML, CSS, Azure, k6, Grafana, Azure DevOps

### Overview

A backend service designed for a border-security/identity-verification workflow. The service receives identity information, communicates with an external identity verification API, processes the response, and provides the verification result to downstream applications.

The project represents a modernized backend architecture where legacy Java functionality can be migrated into **NestJS-based backend services**.

### Key Features

- REST APIs for identity verification
- Integration with external identity/verification APIs
- Request validation and transformation
- Asynchronous processing for external API interactions
- Centralized logging and monitoring
- Error handling and retry-oriented processing
- MongoDB persistence
- API documentation
- High-load and performance testing
- Production-oriented deployment and CI/CD

### Backend

- Developed RESTful APIs using **NestJS and TypeScript**
- Structured the application using NestJS modules, controllers, services, and providers
- Implemented DTO-based request validation
- Integrated with external identity verification services
- Implemented centralized exception handling
- Used **MongoDB** for document-oriented data storage
- Designed reusable service components
- Added structured application logging
- Implemented configuration management for different environments

### Modernization & Migration

- Modernized selected legacy Java functionality into **NestJS backend services**
- Migrated data from **MySQL to MongoDB**
- Used a MongoDB migration tool for relational-to-document data migration
- Designed MongoDB collections according to application access patterns
- Supported coexistence of legacy and modernized services during migration

### Performance & Monitoring

- Used **k6** for API load and performance testing
- Used **Grafana** to visualize performance and monitoring metrics
- Tested API behavior under high request volumes
- Monitored request/response performance and service health
- Focused on scalable asynchronous processing for external API calls

### DevOps

- Used **Azure DevOps** for source control, CI/CD, and release activities
- Supported automated build and deployment pipelines
- Used environment-specific configuration
- Designed the service to be suitable for containerized/cloud deployment

### Example API

```text
POST /api/identity/verify
GET  /api/identity/verification/{id}
GET  /api/health
```

Example flow:

```text
Client Application
       |
       v
NestJS REST API
       |
       +----> Request Validation
       |
       +----> Identity Verification Service
       |             |
       |             v
       |       External Identity API
       |
       v
    MongoDB
       |
       v
Verification Response
```

### Portfolio Value

This project demonstrates experience with **NestJS, TypeScript, Node.js, MongoDB, REST APIs, external API integration, legacy modernization, database migration, performance testing, monitoring, and Azure DevOps**.

---

# Technical Skills Demonstrated

| Area | Technologies |
|---|---|
| Languages | Java, TypeScript, JavaScript, HTML, CSS |
| Backend | Spring Boot, Spring Security, NestJS, Node.js |
| Frontend | HTML, CSS |
| Databases | MySQL, PostgreSQL, MongoDB, Redis |
| API | REST, OpenAPI/Swagger |
| ORM/Data Access | JPA, Hibernate, Spring Data |
| Testing | JUnit, integration testing, k6 |
| Monitoring | Grafana, structured logging |
| DevOps | Azure DevOps, CI/CD, Docker |
| Architecture | Layered architecture, modular backend, service-oriented design |
| Cloud/Deployment | Azure-ready, containerized deployment |

# Suggested Portfolio Positioning

These projects collectively present a profile suitable for **Senior Software Developer / Senior Backend Developer / Full-Stack Developer** roles.

The strongest project for showcasing modern backend expertise is the **Identity Verification & Border Security API**, while the two Java projects demonstrate strong enterprise application development and full-stack capabilities.
