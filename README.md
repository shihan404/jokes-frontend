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



