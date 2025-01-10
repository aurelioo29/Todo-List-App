# 📝 Todo List Application (Fullstack)

A fullstack application for managing tasks, featuring a **React.js** frontend and **Express.js** backend with **MySQL** as the database solution. This project supports complete task management functionality, including task creation, retrieval, updates, and deletion.

---

## 🚀 Features

### Frontend

- Built with **React.js**
- Routing handled by **React Router**
- Task management API integration using **Axios**
- Styled using **Bulma CSS**

### Backend

- RESTful API built with **Express.js**
- **MySQL** for persistent data storage
- **Sequelize ORM** for database management
- CORS enabled for secure cross-origin requests

---

## 📂 Project Structure

```bash
/todo-list-app
├── frontend/
│ ├── public/       # Static files
│ ├── src/          # Frontend logic and components
│ ├── package.json  # Frontend dependencies and scripts
│ └── README.md     # Frontend documentation
├── backend/
│ ├── models/       # Sequelize models
│ ├── routes/       # API routes
│ ├── index.js      # Main server file
│ ├── package.json  # Backend dependencies and scripts
│ └── README.md     # Backend documentation
└── README.md       # Project documentation
```

---

## 🚀 Getting Started

### Prerequisites

- **Node.js**: v14 or later
- **MySQL**: Ensure MySQL is installed and running

---

### Backend Setup

1. Navigate to the backend directory:

   ```bash
   cd backend
   ```

2. Install backend dependencies:

   ```bash
   npm install
   ```

3. Start the backend server:

   ```bash
   npm start
   ```

The backend server will run at http://localhost:5000.

---

### Frontend Setup

1. Navigate to the frontend directory:

   ```bash
   cd frontend
   ```

2. Install frontend dependencies:

   ```bash
   npm install
   ```

3. Start the frontend server:

   ```bash
   npm run dev
   ```

The frontend will run at http://localhost:3000.

## 🌟 API Endpoints

| **Method** | **Endpoint** | **Description**     |
| ---------- | ------------ | ------------------- |
| `GET`      | `/lists`     | Retrieve all tasks  |
| `GET`      | `/lists/:id` | Retrieve task by ID |
| `POST`     | `/lists`     | Create a new task   |
| `PATCH`    | `/lists/:id` | Update task details |
| `DELETE`   | `/lists/:id` | Delete a task by ID |

## 🤝 Contributions

Contributions are welcome! Fork this repository, make changes, and submit a pull request.

---

Developed with ❤️ by **Aurelio**.
