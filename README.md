# Clutch Backend

Welcome to the backend of Clutch! This repository contains the server-side code for managing users, posts, comments, communities, messages, notifications and other social interactions. This README provides an overview of the project structure, setup instructions, and key features.

## Table of Contents

1. [Project Structure](#installation)
2. [Setup Instructions](#setup_instruction)
3. [Key Features](#key_features)
4. [API Documentation](#api)
5. [Contributing](#contributing)

<a name="installation"></a>

## Project Structure

The project structure is organized as follows:

- src/controllers/: Contains controller logic for handling incoming HTTP requests.
- src/db/: Contains database-related files, such as database connection setup.
- src/middleware/: Contains middleware functions used in request processing.
- src/models/: Defines data models and interacts with the database.
- src/routes/: Defines API routes and maps them to controller methods.
- src/services/: Implements business logic and interacts with models.
- src/tests/: Contains unit and integration tests for the backend.
- src/types/: Contains TypeScript type definitions used across the application.
- src/utils/: Contains utility functions used across the application.
- src/app.ts: Entry point for the application.
- src/index.ts: Main file to start the server.

<a name="setup_instruction"></a>

## Setup Instructions

1. Clone this repository:

   ```bash
   git clone https://github.com/realemmanuel/clutch-backend.git
   ```

2. Install Dependencies:

   ```bash
    cd clutch-backend
    npm install
   ```

3. Install Dependencies:

   Create a .env file in the root directory and configure environment variables such as database connection strings, API keys, and other settings.

4. Start the Server:

   ```bash
   npm run dev
   ```

5. Testing:

   Run tests to ensure everything is working correctly:

   ```bash
   npm test
   ```

<a name="key_features"></a>

## Key Features

- User Management: Register new users, authenticate users, update profiles, and manage user settings.
- Post Management: Create, read, update, and delete posts. Users can share their thoughts and multimedia content.
- Commenting: Users can comment on posts and engage in discussions.
- Likes and Dislikes: Users can express their opinion on posts by liking or disliking them.
- Followers/Following: Users can follow other users to stay updated with their posts.
- Notifications: Users receive notifications for new comments, likes, or follows.
- Search: Users can search for posts, users, or hashtags.
- Communities: Users can create and join community and engage in discussions
- Messages: Users can send messages to other users and receive notifications
- Trending: Users can find communities that are currently trending (active) then join community

<a name="api"></a>

## API Documentation

For detailed documentation on the backend API endpoints, refer to the [API documentation]() file.

<a name="contributing"></a>

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request. Make sure to follow the [contributing guidelines]().
