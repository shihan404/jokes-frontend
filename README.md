# joke-frontend

A Next.js application for delivering, submitting, and moderating jokes.

## Overview

**joke-frontend** is a web application built with Next.js that interfaces with several backend services to provide users with a complete joke-sharing experience. Users can view jokes, submit new ones, and moderators can review and approve submissions.

## Features

- **Deliver Jokes**: Fetch and display jokes from the delivery service.
- **Submit Jokes**: Allow users to submit their own jokes.
- **Moderate Jokes**: Provide moderation tools for joke submissions.

## Getting Started

### Prerequisites

- **Node.js** (v14.x.x or later)
- **npm** or **yarn**

### Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/yourusername/joke-frontend.git
   cd joke-frontend
   ```
   ###Install dependencies
 ```bash
   npm install
# or
yarn install
   ```

###Configure environment variables

```bash
NEXT_PUBLIC_DELIVER_JOKES_URL=http://localhost:5000
NEXT_PUBLIC_SUBMIT_JOKES_URL=http://localhost:5005
NEXT_PUBLIC_MODERATE_JOKES_URL=http://localhost:5001
```

### Scripts

Here is a list of useful scripts for development and production:

- `npm run dev` or `yarn dev`: Start the development server.
- `npm run build` or `yarn build`: Build the application for production.
- `npm start` or `yarn start`: Start the production server.
- `npm run lint` or `yarn lint`: Run ESLint checks.
- `npm run format` or `yarn format`: Format the codebase with Prettier.

Additional test and setup scripts based on the package configuration:

- `npm run test` or `yarn test`: Runs formatting, linting, and builds for testing.
- `npm run prepare`: Prepare Git hooks with Husky.

### Tools and Technologies

This project leverages a variety of tools and technologies to support development, testing, and deployment.

#### AI Tools
- **ChatGPT**: Used for assistance in code generation, documentation, and troubleshooting.
- **Claude.ai**: Provides advanced AI capabilities for content generation and interaction.

#### Backend
- **Node.js**: JavaScript runtime environment for server-side code execution.
- **Express**: Web application framework for building RESTful APIs.
- **NestJS** (optional, if using in other services): A progressive Node.js framework for scalable and efficient backend services.
- **Mongoose**: Object Data Modeling (ODM) library for MongoDB and Node.js, used for data management and schema validation.
- **JWT (JSON Web Token)**: Used for secure authentication and authorization.

#### Security
- **Helmet**: Middleware for securing HTTP headers.
- **Express Rate Limit**: Protects APIs by limiting repeated requests.
- **bcrypt.js**: For hashing passwords and securing sensitive data.

#### API Documentation
- **Swagger**: Provides interactive API documentation for easy testing and integration.

#### Development Tools
- **Nodemon**: Utility that automatically restarts the server on code changes.
- **ESLint**: Linter for identifying and fixing code issues.
- **Prettier**: Code formatter to maintain consistent code style.
- **Husky**: Git hooks manager to enforce checks before commits.

#### Environment Management
- **dotenv**: Loads environment variables from `.env` files, ensuring configurations are securely managed.

#### Database
- **MongoDB**: NoSQL database used for storing jokes and user data.
- **MySQL** (if applicable in other services): Relational database management system.

This combination of tools and technologies ensures a robust, secure, and scalable application architecture, suitable for modern web applications.

