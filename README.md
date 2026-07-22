# Cloud AWS Task Manager API

## Developed By

**Thoshan Sathi Vel SK**

---

## Project Overview

Cloud AWS Task Manager API is a production-ready backend application developed using Node.js, Express.js, PostgreSQL, and Prisma ORM. The application provides secure authentication, task management, health monitoring, and cloud deployment support using Docker, AWS, Terraform, and Kubernetes.

This project demonstrates the implementation of cloud-native backend development practices with scalable architecture and deployment-ready infrastructure.

---

## Technology Stack

- Node.js
- Express.js
- PostgreSQL
- Prisma ORM
- JWT Authentication
- Express Validator
- Docker
- Docker Compose
- Nginx
- AWS EC2
- GitHub Actions
- Terraform
- Kubernetes
- Jest
- ESLint

---

## Features

- Secure User Registration and Login
- JWT Authentication
- Task CRUD Operations
- Task Categories
- Task Priorities
- Task Status Management
- Due Dates
- Search, Filtering and Pagination
- Input Validation
- Error Handling Middleware
- Structured Logging
- Health Check APIs
- Swagger API Documentation
- Docker Support
- AWS Deployment Ready
- Kubernetes Configuration
- Terraform Infrastructure

---

## Project Structure

```
src/
 ├── config/
 ├── controllers/
 ├── middleware/
 ├── models/
 ├── routes/
 ├── services/
 ├── utils/
 ├── validators/

prisma/
scripts/
tests/
terraform/
k8s/
nginx/
```

---

## Installation

Clone the repository

```bash
git clone https://github.com/thoshan31/cloud_AWS_Task_Manager.git
```

Move into the project

```bash
cd cloud_AWS_Task_Manager
```

Install dependencies

```bash
npm install
```

Generate Prisma Client

```bash
npm run prisma:generate
```

Run database migrations

```bash
npm run prisma:migrate
```

Start the development server

```bash
npm run dev
```

---

## Environment Variables

Create a `.env` file using `.env.example`.

Required variables:

- PORT
- NODE_ENV
- DATABASE_URL
- JWT_SECRET
- JWT_EXPIRES_IN
- CORS_ORIGIN
- LOG_LEVEL
- SWAGGER_ENABLED

---

## API Base URL

```
http://localhost:3000
```

---

## API Documentation

Swagger UI

```
http://localhost:3000/api-docs
```

---

## Available API Routes

### Authentication

- POST /api/v1/auth/register
- POST /api/v1/auth/login

### Tasks

- GET /api/v1/tasks
- POST /api/v1/tasks
- GET /api/v1/tasks/:taskId
- PATCH /api/v1/tasks/:taskId
- DELETE /api/v1/tasks/:taskId

### Health

- GET /api/v1/health
- GET /api/v1/health/live
- GET /api/v1/health/ready

---

## Testing

Run tests

```bash
npm test
```

Run linting

```bash
npm run lint
```

---

## Docker

Build and start the application

```bash
docker compose up --build
```

---

## Cloud Infrastructure

This project includes deployment-ready configuration for:

- AWS EC2
- Docker
- GitHub Actions
- Terraform
- Kubernetes
- Nginx Reverse Proxy

---

## Author

**Thoshan Sathi Vel SK**

B.Tech Computer Science and Engineering (Software Product Engineering)

Alliance University

---

## License

MIT License

Copyright (c) 2026 Thoshan Sathi Vel SK