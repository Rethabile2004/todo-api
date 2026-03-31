# ASP.NET Core Web API – TodoApi

A RESTful Web API built with ASP.NET Core as part of the official Microsoft tutorial.

## What I Built

A CRUD API for managing todo items, backed by an in-memory database using Entity Framework Core.

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/api/todoitems` | Get all todo items |
| GET | `/api/todoitems/{id}` | Get a single item by ID |
| POST | `/api/todoitems` | Create a new item |
| PUT | `/api/todoitems/{id}` | Update an existing item |
| DELETE | `/api/todoitems/{id}` | Delete an item |

## Concepts Covered

- Controller-based Web API with `[ApiController]`
- Attribute routing with `[HttpGet]`, `[HttpPost]`, `[HttpPut]`, `[HttpDelete]`
- Entity Framework Core with an in-memory database
- Dependency injection of `DbContext` into controllers
- `CreatedAtAction` for returning HTTP 201 with a `Location` header
- Data Transfer Objects (DTOs) to prevent over-posting
- Testing endpoints with `.http` files and Endpoints Explorer

## Tech Stack

![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![ASP.NET Core](https://img.shields.io/badge/ASP.NET_Core-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![Entity Framework](https://img.shields.io/badge/Entity_Framework-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black)
- .NET 9
- ASP.NET Core Web API
- Entity Framework Core (InMemory)
- OpenAPI / Swagger

## Reference

[Microsoft Learn – Create a controller-based Web API with ASP.NET Core](https://learn.microsoft.com/en-us/aspnet/core/tutorials/first-web-api)
