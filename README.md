# .NET Software Engineer

### ASP.NET Core · Backend Systems · Enterprise APIs · Cloud Application Development

I’m a .NET Software Engineer focused on building reliable backend systems and business applications with **C#, .NET 10, ASP.NET Core, Web APIs, Entity Framework Core, and SQL Server**.

My work is centered on maintainable application architecture, secure API design, data access, caching, external system integration, resilience, observability, testing, containerization, and cloud delivery.

Before focusing on software engineering, I led international IT and digital transformation initiatives across Europe. That experience continues to shape how I approach technical solutions — with attention to business requirements, maintainability, collaboration, and long-term system evolution.

## Engineering Focus

* **Backend & API Engineering** — ASP.NET Core, REST APIs, MVC, Dependency Injection, configuration, and structured error handling
* **Data & Persistence** — SQL Server, Entity Framework Core, LINQ, Code-First, Database-First, migrations, pagination, and optimistic concurrency
* **Security** — ASP.NET Core Identity, authentication, role-based authorization, and user-owned resources
* **Caching & Integration** — Redis, in-memory caching, cache invalidation, HttpClient, and external API integration
* **Reliability & Observability** — timeout, retry and fallback strategies, health checks, structured logging, and OpenTelemetry
* **Testing & Delivery** — xUnit, Moq, integration testing, Docker, Docker Compose, GitHub Actions, GHCR, and Azure

---

## Flagship Project

### [EnterpriseOperationsAPI](https://github.com/AlanRacic/EnterpriseOperationsAPI)

Enterprise-oriented ASP.NET Core Web API designed around maintainability, reliability, observability, and production-oriented delivery practices.

The solution applies **Clean Architecture** across Domain, Application, Infrastructure, and API layers and combines several concerns commonly found in long-lived backend systems:

* ASP.NET Core Identity with role-based authorization
* EF Core and SQL Server with pagination, filtering, sorting, indexing, and optimistic concurrency
* Redis and in-memory caching with version-based cache invalidation
* Resilient external HTTP integration with timeout, retry, and fallback behavior
* OpenTelemetry tracing, structured logging, and health checks
* Hangfire background processing
* Unit and integration testing with xUnit, Moq, WebApplicationFactory, and Testcontainers
* Docker and Docker Compose
* GitHub Actions CI/CD and container publishing to GHCR
* Azure Container Apps and Azure SQL deployment using federated OIDC authentication

The repository README documents the architecture, design decisions, request flows, infrastructure setup, testing strategy, and deployment process.

---

## Selected Projects

### [WebShopMVC](https://github.com/AlanRacic/WebShopMVC)

ASP.NET Core MVC e-commerce application implementing end-to-end business workflows including authentication, role-based administration, product management, shopping cart, checkout, order processing, EF Core persistence, and containerized SQL Server deployment with Docker Compose.

### [WeatherGatewayAPI](https://github.com/AlanRacic/WeatherGatewayAPI)

Focused ASP.NET Core integration API demonstrating external HTTP communication, typed `HttpClient`, configurable service integration, JWT-protected endpoints, structured logging and error handling, and automated deployment to Azure App Service through GitHub Actions.

### [MovieManagementAPI](https://github.com/AlanRacic/MovieManagementAPI)

Multi-project ASP.NET Core solution separating a REST API, MVC consumer, EF Core persistence layer, and xUnit tests. The MVC application consumes the API through HTTP/JSON communication while repository abstractions isolate data access from the API layer.

### [InvoiceManagementMVC](https://github.com/AlanRacic/InvoiceManagementMVC)

Business-oriented ASP.NET Core MVC application built with **Entity Framework Core Database-First**, demonstrating reverse-engineered SQL Server models, relational invoice and line-item data, LINQ-based data access, and partial-class extensions of scaffolded entities.

### [TodoListAPI](https://github.com/AlanRacic/TodoListAPI)

ASP.NET Core application combining an authenticated REST API and MVC interface for user-owned todo lists and tasks, using ASP.NET Core Identity, EF Core Code-First, SQL Server, and asynchronous data access.

---

## Technology Stack

**Backend**
C# · .NET 10 · ASP.NET Core · Web APIs · MVC · REST

**Data**
SQL Server · Entity Framework Core · LINQ · Code-First · Database-First · Redis

**Architecture & Reliability**
Clean Architecture · Dependency Injection · Repository Pattern · Caching · Resilience · Optimistic Concurrency · OpenTelemetry · Hangfire

**Security**
ASP.NET Core Identity · Authentication · Authorization · JWT

**Testing**
xUnit · Moq · Integration Testing · WebApplicationFactory · Testcontainers

**Cloud & Delivery**
Azure · Docker · Docker Compose · GitHub Actions · CI/CD · GHCR

**Supporting Front-End**
Razor · HTML · CSS · JavaScript · TypeScript · React

---

## Connect

* [LinkedIn](https://www.linkedin.com/in/alanracic)
* Email: [alan.racic@gmail.com](mailto:alan.racic@gmail.com)
