# TaskForge - MERN Stack Task Manager

TaskForge is a powerful task management application built on the MERN (MongoDB, Express.js, React, Node.js) stack. It provides a seamless and efficient way to manage your tasks and stay organized. This README will guide you through the steps required to initialize the project.

## Getting Started

### Prerequisites

Before you begin, make sure you have the following installed on your machine:

- Node.js and npm (Node Package Manager)
- MongoDB (Make sure it's running)

### Installation

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/your-username/TaskForge.git
   ```

2. Change into the project directory:

   ```bash
   cd TaskForge
   ```

3. Install server dependencies:

   ```bash
   npm install
   ```

4. Change into the client directory:

   ```bash
   cd client
   ```

5. Install client dependencies:

   ```bash
   npm install
   ```

6. Return to the project root directory:

   ```bash
   cd ..
   ```

7. Create a `.env` file in the project root and configure your MongoDB connection:

   ```env
   MONGODB_URI=your_mongodb_connection_string
   ```

### Running the Application

1. In the project root directory, start the server:

   ```bash
   npm start
   ```

2. Open a new terminal, change into the `client` directory, and start the React app:

   ```bash
   cd client
   npm start
   ```

The TaskForge application should now be running locally. Open your web browser and navigate to `http://localhost:3000` to access the application.

### Features

- Create, edit, and delete tasks
- Mark tasks as completed
- Filter tasks based on their status
- User authentication (TODO: Add authentication details)

Feel free to explore the codebase and customize the application according to your needs. Happy task managing with TaskForge!