
# Todo List Application

This is a simple **Todo List Application** built using the **MERN stack** (MongoDB, Express, React, Node.js). The application allows users to:

- Add tasks
- Update tasks (mark as done or undone)
- Delete tasks

## Features

- **Add Tasks:** Easily add new tasks to the list.
- **Update Tasks:** Mark tasks as completed or revert them to incomplete.
- **Delete Tasks:** Remove tasks from the list.

## Technologies Used

- **Frontend:** React
- **Backend:** Node.js and Express.js
- **Database:** MongoDB

## Getting Started

Follow the steps below to run the application locally.

### Prerequisites

Ensure you have the following installed:

- Node.js
- MongoDB

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/todolist.git
   cd todolist
   ```

2. Install dependencies for both the client and server:
   ```bash
   # Install backend dependencies
   cd server
   npm install

   # Install frontend dependencies
   cd ../client
   npm install
   ```

3. Start MongoDB:
   Make sure your MongoDB server is running locally on `mongodb://localhost:27017`.

4. Run the application:

   - Start the backend:
     ```bash
     cd server
     npm start
     ```

   - Start the frontend:
     ```bash
     cd client
     npm start
     ```

5. Open your browser and navigate to:
   ```
   http://localhost:3000
   ```

