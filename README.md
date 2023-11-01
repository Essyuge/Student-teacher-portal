# Teacher-Student Portal Backend API (Ruby on Rails)

Welcome to the Teacher-Student Portal Backend API documentation. This API, built with Ruby on Rails, powers a comprehensive platform that facilitates communication, management, and interaction between teachers and students. It offers a wide range of features designed to enhance the educational experience.

## Table of Contents
- [Features](#features)
- [API Endpoints](#api-endpoints)
- [Getting Started](#getting-started)
- [Authentication](#authentication)
- [Error Handling](#error-handling)
- [Data Validation](#data-validation)
- [Sample Requests and Responses](#sample-requests-and-responses)
- [Contributing](#contributing)
- [License](#license)

## Features

### Teacher Management
1. Teachers can register, log in, and manage their accounts.
2. Teachers can change their passwords as necessary.
3. Teachers can store and manage course materials, lecture notes, and resources.

### Class Management
4. Teachers can create and manage classes.
5. Teachers can add or remove a student from their class.

### Grading and Assessment
6. Teachers can add or update their student's grades.
7. Teachers can provide feedback to students.

### Communication
8. Teachers can post notices, which are sent to all students in their class.
9. Teachers can create and upload assignments for students to complete.
10. Teachers can see all the marks given to a student through their marks profile.
11. Students can submit assignments, but once submitted, changes are not allowed.

### Student Features
12. Students can view their marks in the marks section.
13. Students can see the list of all teachers in the portal 

### Search

14. Teachers can search for any student through the search option at the top of the student list page.

## API Endpoints

For a detailed list of API endpoints and their functionality, please refer to the [API Documentation](api-documentation.md).

## Getting Started

To get started with this API, follow these steps:

1. Clone the repository: `git clone https://github.com/your-repo.git`
2. Install Ruby and Rails if not already installed.
3. Install dependencies: `bundle install`
4. Set up the database and environment variables.
5. Run the Rails server: `rails server`
6. Access the API at `http://localhost:3000` (or your chosen port).

## Authentication

This API uses JSON Web Tokens (JWT) for user authentication. When making requests to protected endpoints, provide an `Authorization` header with a valid token.

## Error Handling

The API provides detailed error responses to assist in troubleshooting issues. Please refer to the [Error Handling Guide](error-handling.md) for more information.

## Data Validation

To maintain data integrity and security, the API enforces strict data validation. Please refer to the [Data Validation Guide](data-validation.md) for more information.

## Sample Requests and Responses

For examples of API requests and responses, consult the [Sample Requests and Responses](sample-requests-responses.md) document.

## Contributing

We welcome contributions from the community. To contribute, please follow our [Contribution Guidelines](CONTRIBUTING.md).

## License

This project is licensed under the [MIT License](LICENSE).
