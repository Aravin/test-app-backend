# Test App Backend

NestJS backend application with GraphQL support.

## Setup

1. Install dependencies:
```bash
npm install
```

2. Start the development server:
```bash
npm run start:dev
```

The GraphQL playground will be available at `http://localhost:4000/graphql`

## Features

- NestJS framework
- GraphQL API with Apollo Server
- CORS enabled for frontend connection
- Sample Users module with queries and mutations

## GraphQL Endpoints

- Query `users`: Get all users
- Query `user(id: String!)`: Get a single user by ID
- Mutation `createUser(createUserInput: CreateUserInput!)`: Create a new user
- Mutation `deleteUser(id: String!)`: Delete a user by ID

## Scripts

- `npm run build` - Build the application
- `npm run start` - Start the application
- `npm run start:dev` - Start in development mode with hot reload
- `npm run start:prod` - Start in production mode
