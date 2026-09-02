# Nest Clean

A study API that combines NestJS with Clean Architecture and domain-oriented design.

## Project goal

Understand how a framework such as NestJS can remain at the infrastructure boundary while application rules stay isolated, testable and independent.

## Features

- Authentication with JWT and asymmetric keys
- Persistence through Prisma and PostgreSQL
- Use cases separated from controllers and database adapters
- Unit and end-to-end test suites

## Technologies

- **TypeScript**
- **Node.js**
- **NestJS**
- **Prisma**
- **PostgreSQL**
- **Vitest**
- **JWT**
- **Zod**

## What I learned

- Integrating NestJS without coupling domain rules to the framework
- Applying dependency inversion through ports and adapters
- Testing use cases independently from infrastructure
- Validating HTTP input and authentication boundaries

## Running locally

```bash
npm install
docker compose up -d
npm run start:dev
```

## About this repository

This repository documents a learning project and the technical decisions explored while building it. It is not presented as a production-ready system.
