# Supermarket API

Simple RESTful API built with ASP.NET Core 3.1 using a decoupled, maintainable architecture.

## Changes list

## Frameworks and Libraries
- [ASP.NET Core 2.2](https://docs.microsoft.com/pt-br/aspnet/core/?view=aspnetcore-2.2);
- [Entity Framework Core](https://docs.microsoft.com/en-us/ef/core/) (for data access);
- [Entity Framework In-Memory Provider](https://docs.microsoft.com/en-us/ef/core/miscellaneous/testing/in-memory) (for testing purposes);
- [AutoMapper](https://automapper.org/) (for mapping resources and models);
- [Swashbuckle](https://github.com/domaindrivendev/Swashbuckle) (API documentation).

## How to Test

First, install [.NET Core 2.2](https://dotnet.microsoft.com/download/dotnet-core/2.2). Then, open the terminal or command prompt at the API root path (```/src/Supermarket.API/```) and run the following commands, in sequence:

```
dotnet restore
dotnet run
```

Navigate to ```https://localhost:5001/api/products``` to check if the API is working. If you see a HTTPS security error, just add an exception to see the results.

Navigate to ```https://localhost:5001/swagger``` to check the API documentation.

![API Documentation](https://raw.githubusercontent.com/evgomes/supermarket-api/master/images/swagger.png)
