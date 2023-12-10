# Task Management API

This is a Django-based RESTful API for managing tasks. It allows users to create tasks, update their status, and set due dates.

## Table of Contents

- [Features](#features)
- [Endpoints](#endpoints)
- [Setup](#setup)
- [Usage](#usage)
- [Authentication](#authentication)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [License](#license)

## Features

- Task CRUD Operations
- Task Status
- User Authentication
- Permissions

## Endpoints

- **GET /tasks/**
- **POST /tasks/**
- **GET /tasks/{id}/**
- **PUT /tasks/{id}/**
- **DELETE /tasks/{id}/**

For more detailed API documentation, access the Swagger documentation and use the provided authorization feature.

Swagger URL: [Swagger Documentation](http://your-api-url/swagger/)
Redoc URL: [Redoc Documentation](http://your-api-url/redoc/)

## Setup

1. Clone the repository:

2. Install dependencies:

3. Run migrations:

4. Start the server:

## Usage


- Registration:
- `POST /register/` - Register a new user by providing a username and password.

- Login:
- `POST /login/` - Log in by providing the registered username and password. This will return an access token.

- Access Swagger:
- Go to the [Swagger Documentation](http://your-api-url/swagger/).
- Click on the "Authorize" button.
- Enter the obtained access token prefixed by "Bearer " in the "Value" field.
- Click "Authorize" to apply the token.
- You can now explore and test the API endpoints.

## Authentication

JWT authentication is used. Include the token in the Authorization header.


## Dependencies

This project uses Django, Django REST framework, and other dependencies listed in `requirements.txt`.

## Contributing

Feel free to open issues or submit pull requests for any improvements or additional features.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -am 'Add your feature'`)
4. Push to the branch (`git push origin feature/YourFeature`)
5. Open a Pull Request

