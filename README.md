# ContosoPizza

An ASP.NET Core Web API project built as part of CSE 325 at BYU-Idaho. The API supports full CRUD operations for managing pizza data using ASP.NET Core controllers.

## Tech Stack
- .NET 10
- ASP.NET Core Web API
- C#

## Endpoints
- `GET /pizza` - Get all pizzas
- `GET /pizza/{id}` - Get pizza by ID
- `POST /pizza` - Add a new pizza
- `PUT /pizza/{id}` - Update a pizza
- `DELETE /pizza/{id}` - Delete a pizza

## Setup
1. Clone the repository
2. Run `dotnet restore`
3. Run `dotnet run`
4. Test endpoints using the included `ContosoPizza.http` file in VS Code