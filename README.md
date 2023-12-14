
```markdown
# Customer Supplier Chaining API - ASP.NET Core

![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)

## Overview

This project is an implementation of a full-fledged shopping API using ASP.NET Core with Onion Architecture. The API supports two roles - Customer and Supplier, each with distinct functionalities. JWT authentication is implemented to secure the API, and middleware is used for additional features.

## Features

- **Onion Architecture:** The project follows the Onion Architecture, providing a clear separation of concerns and making the codebase maintainable and scalable.

- **JWT Authentication:** JSON Web Token (JWT) authentication is implemented to secure the API endpoints. Users need to authenticate to access the protected resources.

- **Middleware:** Middleware is utilized for handling various aspects of the API request/response pipeline, enhancing functionality and providing a seamless experience.

- **Role-based Access:** The API supports two roles - Customer and Supplier. Each role has specific functionalities and access to relevant resources.

- **Product Listing:** Suppliers can list their products, providing details such as name, description, and price.

- **Shopping Cart:** Customers can view products, add them to the cart, and proceed with the purchase.

## Project Structure

The project follows a structured architecture:

- **CustomerSupplierChaining.API:** The main API project.
- **CustomerSupplierChaining.Core:** Core business logic and domain models.
- **CustomerSupplierChaining.Infrastructure:** Infrastructure concerns, such as data access and external integrations.
- **CustomerSupplierChaining.Tests:** Unit tests for the project.

## Getting Started

To run the project locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/pavansonawane2266/Customer-Supplier-Chaining-API-ASP.net.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Customer-Supplier-Chaining-API-ASP.net
   ```

3. Build and run the application:

   ```bash
   dotnet build
   dotnet run
   ```

4. Access the API at `https://localhost:5001` (or a different port if configured).

## API Documentation

For detailed API documentation, please refer to the [API Documentation](docs/API_Documentation.md).

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvement, please open an issue or submit a pull request.

