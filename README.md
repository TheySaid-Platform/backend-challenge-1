# backend-challenge-1

Welcome! This assignment is designed to evaluate your backend engineering skills using modern Node.js technologies and monorepo best practices. Please read the requirements carefully and follow the instructions below.

---

## Assignment Overview

Build a simple backend service for a blog platform. The service should support CRUD operations for blog posts and real-time updates. You will use **Nx**, **NestJS**, **TypeORM**, **PostgreSQL**, and **GraphQL**.

---

## Requirements

### Functional

- **CRUD operations for blog posts** (Create, Read, Update, Delete)
- **GraphQL Query resolvers** for fetching blog posts (all and by ID)
- **GraphQL Mutation resolvers** for creating, updating, and deleting blog posts
- **GraphQL Subscription** for real-time updates when a new post is created

### Technical

- Use **Nx** to scaffold and manage the project
- Use **Nx-recommended folder structure**
- Use **NestJS** as the framework (as an Nx application)
- Use **TypeORM** for database interactions with **PostgreSQL**
- Write the entire application in **TypeScript**
- Implement the **GraphQL API** using `@nestjs/graphql`
- Define the **GraphQL schema using the code-first approach** (TypeScript decorators)
- Implement **basic logging** and **error handling**
- Implement **proper error handling and custom error types** in GraphQL
- Use **DataLoader** to avoid N+1 query problems and for efficient data fetching (if applicable)
- Provide a **Dockerfile** for the application

---

## Deliverables

1. **A GitHub repository** (or a zip file) containing your code and a README with setup instructions. DONOT submit PR.
2. **A Dockerfile** so the application can be run easily in a container.
3. **Clear instructions** on how to run the application locally (with and without Docker).
4. **Sample GraphQL queries/mutations/subscriptions** in your README or as a separate file.

---

## Evaluation Criteria

- Code structure, readability, and maintainability
- Correctness and completeness of the implementation
- Use of best practices (error handling, logging, modularity, etc.)
- Efficient data fetching (use of DataLoader if applicable)
- Proper use of TypeScript, Nx, and NestJS patterns
- Quality of documentation

---

## Getting Started

You are free to use any project structure you prefer within Nx, but here are some resources to help you:

- [Nx Documentation](https://nx.dev/)
- [NestJS Documentation](https://docs.nestjs.com/)
- [TypeORM Documentation](https://typeorm.io/)
- [@nestjs/graphql Documentation](https://docs.nestjs.com/graphql/quick-start)
- [DataLoader](https://github.com/graphql/dataloader)
- [Docker Documentation](https://docs.docker.com/)

---

## Submission

Please submit your solution by sharing a link to your GitHub repository (preferred) or by sending a zip file with your code and instructions.

---

**Good luck! If you have any questions, feel free to reach out.**
