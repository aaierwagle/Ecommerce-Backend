# E-commerce Backend

This project is a backend application for an e-commerce platform, built with Node.js, Express.js, and MongoDB using Mongoose as the ODM (Object Data Modeling) library.

## Acknowledgements

This project was developed as part of a learning experience under the guidance of my MERN stack instructor, Arun Sir. His teachings and resources have been invaluable in building this application.

For more of Arun Sir's work and repositories, you can visit his GitHub profile: [Arun1only1](https://github.com/Arun1only1).


## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [Contributing](#contributing)
- [Acknowledgements](#acknowledgements)
- [License](#license)

## Introduction

This project provides the backend functionality for an e-commerce site, including a RESTful API built with Express.js and Mongoose for database management. It allows for the management of products, categories, and tags, facilitating operations such as creating, updating, and deleting entries in the database.

## Features

- **Express.js API**: A RESTful API to manage e-commerce data.
- **Mongoose ODM**: Simplifies database interactions with MongoDB.
- **CRUD Operations**: Create, read, update, and delete products, categories, and tags.
- **Database Seeding**: Pre-populate the database with sample data for testing.

## Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/aaierwagle/Ecommerce-Backend.git
   cd Ecommerce-Backend
   ```

2. **Install dependencies**:

   ```bash
   npm install
   ```

3. **Configure environment variables**:

   - Create a `.env` file in the root directory.
   - Add the following variables with your database credentials:

     ```env
     DB_URI=mongodb://localhost:27017/your_database_name
     ```

4. **Set up the database**:

   - Ensure MongoDB is running on your local machine or accessible via the provided `DB_URI`.
   - Seed the database with sample data:

     ```bash
     npm run seed
     ```

## Usage

1. **Start the server**:

   ```bash
   npm start
   ```

   The server will run on `http://localhost:3001`.

2. **API Testing**:

   - Use tools like [Insomnia](https://insomnia.rest/) or [Postman](https://www.postman.com/) to test the API endpoints.
   - Ensure the server is running before making requests.

## API Endpoints

- **Categories**:
  - `GET /api/categories`: Retrieve all categories.
  - `GET /api/categories/:id`: Retrieve a single category by ID.
  - `POST /api/categories`: Create a new category.
  - `PUT /api/categories/:id`: Update a category by ID.
  - `DELETE /api/categories/:id`: Delete a category by ID.

- **Products**:
  - `GET /api/products`: Retrieve all products.
  - `GET /api/products/:id`: Retrieve a single product by ID.
  - `POST /api/products`: Create a new product.
  - `PUT /api/products/:id`: Update a product by ID.
  - `DELETE /api/products/:id`: Delete a product by ID.

- **Tags**:
  - `GET /api/tags`: Retrieve all tags.
  - `GET /api/tags/:id`: Retrieve a single tag by ID.
  - `POST /api/tags`: Create a new tag.
  - `PUT /api/tags/:id`: Update a tag by ID.
  - `DELETE /api/tags/:id`: Delete a tag by ID.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes. Ensure that your code follows the project's coding standards and includes appropriate tests.


## License

This project is licensed under the [MIT License](LICENSE).

For a visual guide on building an e-commerce backend, you might find the following video helpful:

 
