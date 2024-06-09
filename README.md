# Retro Groome E-commerce Backend

Welcome to the Retro Groome E-commerce Backend repository! This repository contains the backend codebase for Retro Groome, a clothing brand e-commerce site. We've built this project using the NestJS framework, providing a scalable and maintainable architecture to support our microservices.

## Table of Contents

1. [Introduction](#introduction)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Folder Structure](#folder-structure)
5. [Contributing](#contributing)
6. [License](#license)

## Introduction

Retro Groome E-commerce Backend is designed to handle the backend functionalities of our e-commerce platform. It includes various microservices responsible for different aspects such as user management, product catalog, order processing, and more. Leveraging NestJS, we ensure robustness, scalability, and maintainability.

## Installation

To get started with Retro Groome E-commerce Backend, follow these steps:

1. **Clone the repository:**
   ```
   git clone https://github.com/retrogroome/backend.git
   ```

2. **Install dependencies:**
   ```
   cd backend
   npm install
   ```

3. **Environment setup:**
    - Create a `.env` file based on `.env.example` and fill in the necessary environment variables.

4. **Database setup:**
    - Set up your preferred database (e.g., PostgreSQL, MongoDB) and update the database configuration in `.env`.

5. **Start the server:**
   ```
   npm run start:dev
   ```

## Usage

Once the server is up and running, you can start utilizing the APIs provided by the various microservices. Here are some key endpoints:

- **User Management:** `/api/users`
- **Product Catalog:** `/api/products`
- **Order Processing:** `/api/orders`

Make sure to refer to the API documentation for detailed information on available endpoints and their functionalities.

## Folder Structure

The project follows a structured folder organization to maintain clarity and ease of navigation. Here's an overview:

```
src/
|-- modules/
|   |-- user/
|   |-- product/
|   |-- order/
|   |-- ...
|-- shared/
|   |-- dto/
|   |-- middleware/
|   |-- ...
|-- main.ts
|-- ...
```

- **Modules:** Contains individual modules for different microservices.
- **Shared:** Contains shared utilities, DTOs (Data Transfer Objects), and middleware.

## Contributing

We welcome contributions to Retro Groome E-commerce Backend! If you'd like to contribute, please follow these steps:

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/your-feature`).
3. Commit your changes (`git commit -am 'Add some feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Create a new Pull Request.

## License

This project is licensed under the [MIT License](LICENSE). Feel free to use, modify, and distribute it as per the terms of the license.

---

Happy coding! If you have any questions or need assistance, feel free to reach out to us.