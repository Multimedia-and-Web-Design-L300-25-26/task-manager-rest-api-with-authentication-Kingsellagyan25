# Task Manager REST API with Authentication

This repository contains a Node.js/Express application implementing a simple task manager API protected by JWT authentication. It includes user registration/login and CRUD operations for tasks stored in MongoDB via Mongoose.

## Features

- RESTful API endpoints for managing tasks
- JSON Web Token (JWT) authentication
- Password hashing with bcryptjs
- MongoDB database via Mongoose
- Unit and integration tests with Jest & Supertest

## Getting Started

### Prerequisites

- Node.js 18+
- MongoDB running locally or accessible via URI

### Installation

```bash
npm install
cp .env.example .env  # configure your environment variables
```

### Running

```bash
npm run dev   # start in development with nodemon
npm start      # regular start
```

### Testing

```bash
npm test
```

## Workflow

Pushes to `main` trigger CI via GitHub Actions defined in `.github/workflows/test.yml`.

## License

ISC

