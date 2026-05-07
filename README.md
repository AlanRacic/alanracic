# .NET Developer | C#, .NET 10, ASP.NET Core, MVC, Web APIs, SQL Server  
### Clean Architecture, DDD Fundamentals, Azure Cloud Deployment, Docker

## About

I’m a .NET Developer focused on building scalable, reliable applications with **C#, .NET 10, ASP.NET Core, MVC, Web APIs, and SQL Server**. I prioritize clean, maintainable codebases and apply **Clean Architecture**, **Dependency Injection**, **Repository Pattern**, and **DDD fundamentals** to keep systems well-structured and easy to evolve over time.

My portfolio includes ASP.NET Core MVC and Web API projects with real-world backend patterns such as authentication, authorization, relational data modeling, API integration, structured error handling, and layered application design.

I also work with modern deployment-oriented development workflows, including **Azure Cloud App Service**, **GitHub Actions CI/CD**, **Docker**, **Docker Compose**, and containerized SQL Server environments. These additions demonstrate practical understanding of how .NET applications are built, configured, containerized, and deployed beyond a local development environment.

Before transitioning into software engineering, I led international IT and digital transformation initiatives across Europe. That experience strengthened my ability to translate operational requirements into practical technical solutions and collaborate effectively in cross-functional environments.

### Current focus

- Building ASP.NET Core MVC applications and RESTful Web APIs on .NET 10  
- Designing SQL Server-backed systems with clear data workflows, LINQ, and EF Core migrations  
- Applying Clean Architecture, Repository Pattern, Dependency Injection, and DDD fundamentals  
- Building secure applications with ASP.NET Identity, JWT authentication, and authorization  
- Using Azure Cloud App Service and GitHub Actions for cloud-hosted API deployment  
- Containerizing ASP.NET Core applications with Docker, Docker Compose, and SQL Server containers  
- Writing testable, maintainable code with unit testing tools such as xUnit and Moq  
- Working in structured development environments using Git, GitHub, Jira, Swagger, Postman, and Visual Studio  

---

## Tech Stack

### Core

- C# · .NET 10 · ASP.NET Core · MVC · Web APIs · SQL Server

### Data & Integration

- Entity Framework Core · LINQ · Migrations · Code-First / Database-First · JSON · HttpClient · REST APIs

### Cloud & Deployment

- Azure Cloud App Service · GitHub Actions · CI/CD · Docker · Docker Compose · SQL Server Containers

### Testing & Tools

- Unit Testing · xUnit · Moq · Swagger / OpenAPI · Postman · Visual Studio · Git · GitHub · Jira

### Front-End Supporting Skills

- HTML · CSS · JavaScript (ES6) · TypeScript · React · Razor

### Architecture

- Clean Architecture · Repository Pattern · Dependency Injection · DDD Fundamentals · Layered Architecture

---

## Featured Projects  

### **1) WebShopMVC — Containerized ASP.NET Core MVC eCommerce Application**  

**Tech:** ASP.NET Core MVC (.NET 10) · SQL Server · Entity Framework Core · Identity · Razor · Docker · Docker Compose  

Full-stack eCommerce application implementing end-to-end shopping workflows, authentication, administrative management, and a containerized multi-service setup using Docker Compose with SQL Server container support.

**Highlights**  

- Implemented Identity-based authentication with role-based authorization  
- Built an Admin area for managing products, categories, and images  
- Developed shopping cart, checkout flow, and order lifecycle handling  
- Applied LINQ-based filtering and pagination for efficient data access  
- Structured the application using layered architecture with Dependency Injection and repository/service patterns  
- Added Docker support for containerized ASP.NET Core MVC application execution  
- Configured Docker Compose with an application container and SQL Server container  
- Applied EF Core migrations during application startup for reproducible database setup  

**Repository:**  
https://github.com/alanracic/WebShopMVC  

---

### **2) WeatherGatewayAPI — Azure Cloud-Deployed ASP.NET Core Web API**  

**Tech:** ASP.NET Core Web API · JWT Authentication · HttpClient · DTOs · Azure Cloud App Service · GitHub Actions CI/CD  

Backend API acting as a gateway to an external weather service, demonstrating secure API design, external service integration, structured error handling, and cloud-hosted deployment using Azure Cloud App Service.

**Highlights**  

- Implemented JWT-based authentication and secured endpoints using `[Authorize]`  
- Integrated external API communication via HttpClient with configurable base URL and timeout  
- Applied DTO mapping to transform external responses into internal API models  
- Built global exception handling middleware for consistent JSON error responses  
- Used structured logging with ILogger for request tracking and diagnostics  
- Designed clear separation between controller, service, and integration layers  
- Deployed the API to Azure Cloud App Service with a public Swagger / OpenAPI endpoint  
- Integrated GitHub Actions CI/CD workflow for automated build and deployment  

**Live Cloud Demo:**  
https://weathergatewayapi-a8hqgeavazg6a5c3.italynorth-01.azurewebsites.net/swagger  

**Repository:**  
https://github.com/alanracic/WeatherGatewayAPI  

---

### **3) MovieManagementAPI — ASP.NET Core Web API & MVC Client**  

**Tech:** ASP.NET Core Web API · ASP.NET Core MVC · SQL Server · Entity Framework Core · HttpClient · JSON  

RESTful Web API for managing movie data, paired with a separate ASP.NET Core MVC client that consumes the API through structured HTTP communication.  

**Highlights**  

- Designed and implemented REST endpoints supporting full CRUD operations  
- Applied asynchronous request handling using async/await  
- Implemented Data Transfer Objects (DTOs) to decouple API and client models  
- Used the Repository Pattern to separate business logic from data access  
- Enabled structured JSON request/response handling between API and client  
- Added filtering and sorting logic for efficient data retrieval  

**Repository:**  
https://github.com/alanracic/MovieManagementAPI  

---

### **4) InvoiceManagementMVC — ASP.NET Core MVC (Database-First)**

**Tech:** ASP.NET Core MVC · SQL Server · Entity Framework Core (Database-First) · LINQ · Razor  

Business-oriented invoice management system built using a Database-First approach, focusing on structured data handling, calculations, and clear presentation of financial records.

**Highlights**

- Reverse-engineered SQL Server schema using Entity Framework Core Database-First scaffolding  
- Implemented invoice and line-item workflows with reliable totals calculation  
- Used LINQ queries for filtering, aggregation, and summary views  
- Built Razor-based UI for full CRUD operations and data presentation  
- Extended scaffolded models using partial classes to preserve clean structure  

**Repository:**  
https://github.com/alanracic/InvoiceManagementMVC

---

### **5) TodoListAPI — ASP.NET Core Web API (Code-First)**

**Tech:** ASP.NET Core Web API · SQL Server · Entity Framework Core · Swagger / OpenAPI  

Minimal RESTful API for task management, focused on clean structure, predictable behavior, and maintainable data access.

**Highlights**

- Code-First domain models with Entity Framework Core migrations  
- Async CRUD endpoints following REST conventions  
- Input validation and consistent HTTP responses  
- Swagger-based API documentation for testing and inspection  
- Layered structure with Dependency Injection and repository/service separation  

**Repository:**  
https://github.com/alanracic/TodoListAPI

---

### **6) StudentManagementApp — ASP.NET Core MVC (Code-First + LINQ)**

**Tech:** ASP.NET Core MVC · SQL Server · Entity Framework Core (Code-First) · LINQ · Razor  

Student and grade management application focused on relational data modeling, seeded datasets, and query-driven presentation logic.

**Highlights**

- Code-First domain modeling with Entity Framework Core migrations  
- Seeded relational data with students, grades, and subjects  
- LINQ-based filtering, grouping, and projection for reporting-style views  
- Razor UI for structured data display and navigation  

**Repository:**  
https://github.com/alanracic/StudentManagementApp

---

## Portfolio Focus

This portfolio demonstrates practical .NET development across:

- ASP.NET Core MVC applications  
- RESTful Web APIs  
- SQL Server-backed systems  
- Entity Framework Core workflows  
- Authentication and authorization  
- External API integration  
- Azure Cloud App Service deployment  
- GitHub Actions CI/CD  
- Docker and Docker Compose containerization  
- Clean, layered backend architecture  

---

## Connect

- LinkedIn: https://www.linkedin.com/in/alanracic  
- Email: alan.racic@gmail.com

---

## Career Direction

I focus on building enterprise-grade .NET systems with strong architecture, reliable data workflows, clean APIs, and practical deployment awareness. My long-term goal is to contribute to long-lived codebases, deeper architectural responsibilities, and technical leadership within the .NET ecosystem.
