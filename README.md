# 🔐 JWT User Authentication & CRUD Operations

A Full-Stack **JWT User Authentication & CRUD Operations** application built using **React**, **Express.js**, and **JSON Web Token (JWT)**. This project demonstrates secure user authentication along with complete CRUD (Create, Read, Update, Delete) operations on protected resources using REST APIs.

---

## 📌 Project Overview

This application allows users to register, log in securely using JWT authentication, and perform CRUD operations after successful authentication. Protected API routes ensure that only authenticated users can access or modify data.

---

## ✨ Features

- 👤 User Registration
- 🔑 Secure User Login
- 🔐 JWT Token Generation
- 🛡️ Protected API Routes
- ➕ Create Records
- 📄 View Records
- ✏️ Update Records
- ❌ Delete Records
- 🚪 User Logout
- ⚡ Responsive React User Interface
- 🌐 REST API Integration

---

## 📁 Project Structure

```text
project-folder/
│
├── backend/
│   └── index.js
│
├── frontend/
│   └── src/
│       ├── App.jsx
│       └── App.css
│
└── README.md
```

---

## 🛠️ Technologies Used

### Frontend
- React
- Vite
- CSS3
- Fetch API

### Backend
- Node.js
- Express.js
- JSON Web Token (JWT)
- CORS
- Database (SQLite / MongoDB / MySQL depending on your implementation)

---

## 🔄 Authentication Workflow

1. User registers with valid details.
2. User logs in using registered credentials.
3. Server validates the credentials.
4. A JWT token is generated and returned to the client.
5. The client stores the token securely.
6. The token is included in the `Authorization` header for protected requests.
7. The server verifies the token before allowing CRUD operations.

---

## 🔗 REST API Endpoints

### Authentication

| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | `/register` | Register a new user |
| POST | `/login` | Authenticate user and generate JWT |

### User CRUD

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/users` | Retrieve all users |
| GET | `/users/:id` | Retrieve a user by ID |
| POST | `/users` | Create a new user |
| PUT | `/users/:id` | Update user details |
| DELETE | `/users/:id` | Delete a user |

> **Note:** CRUD endpoints are protected and require a valid JWT token.

---

## 🔑 Authorization Header

Include the JWT token in every protected request:

```http
Authorization: Bearer <your_jwt_token>
```

---

## ▶️ Running the Backend

1. Open a terminal.

2. Navigate to the backend folder:

```bash
cd backend
```

3. Start the server:

```bash
node index.js
```

Backend runs at:

```text
http://localhost:5000
```

---

## ▶️ Running the Frontend

1. Open another terminal.

2. Navigate to the frontend folder:

```bash
cd frontend
```

3. Start the React application:

```bash
npm run dev
```

Frontend runs at:

```text
http://localhost:5173
```

---

## 📦 Installation

### Backend

```bash
cd backend
npm install
node index.js
```

### Frontend

```bash
cd frontend
npm install
npm run dev
```

---

## 📸 Application Workflow

1. Register a new account.
2. Log in using valid credentials.
3. Receive a JWT token.
4. Store the token on the client.
5. Access protected pages.
6. Create new records.
7. View existing records.
8. Update record information.
9. Delete unwanted records.
10. Log out.

---

## 🎯 Learning Objectives

This project demonstrates:

- JWT Authentication
- User Registration and Login
- Authentication vs Authorization
- Protected Routes
- Express Middleware
- CRUD Operations
- REST API Development
- React Hooks (`useState`, `useEffect`)
- Frontend and Backend Integration
- Secure Token-Based Authentication

---

## 🚀 Future Enhancements

- Password Hashing using bcrypt
- Refresh Tokens
- Role-Based Access Control (RBAC)
- User Profile Management
- Search and Filter Functionality
- Pagination
- Form Validation
- Email Verification
- Password Reset
- Docker Deployment

---

## 👩‍💻 Author

**Sneha Hiremath**

---

## 📄 License

This project is created for educational and learning purposes.
