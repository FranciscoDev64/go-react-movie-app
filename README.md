# Go + React Movie App

A full-stack **movie catalog web application** built with **React (front end)** and **Go (back end)** — demonstrating a real-world, **production-ready** developer workflow. This project was developed while completing the Udemy course *“Working with React and Go (Golang)”*, where I learned how to build, secure, query, and deploy a modern web application with best practices. :contentReference[oaicite:1]{index=1}

---

## 🚀 Project Overview

This application allows users to:

✔️ Register and log in securely  
✔️ Browse a movie catalog  
✔️ Filter movies by genre  
✔️ Perform full CRUD operations (Create, Read, Update, Delete)  
✔️ Request data via both REST and GraphQL endpoints  

The back end is written in **Go (Golang)** and the front end in **React (React 18 + Router 6)**, connected to a **PostgreSQL** database and secured using **JWT authentication**. :contentReference[oaicite:2]{index=2}

---

## 🔧 Tech Stack

### Front End
- **React** — SPA with modern hooks and component design
- **React Router v6** — declarative routing
- Built with performance and scalability in mind

### Back End
- **Go (Golang)** — fast, type-safe REST & GraphQL APIs
- **JWT Authentication** — access tokens and refresh tokens
- **PostgreSQL** — relational database
- JSON helpers for robust request/response handling

### Tooling
- Docker & Docker Compose for local development
- Feature branches & Git best practices
- Professional commit history and branch naming

---

## 🧠 Key Features Built

### 1. Project Initialization  
- Created a clean repo with feature branches
- Structured the back end and front end directories

### 2. User Auth & JWT  
- Secure login and signup
- JWT access & refresh token strategy

### 3. REST API with Go  
- JSON body handling
- Postgres persistence
- Validation and error handling

### 4. CRUD for Movies  
- Full create/read/update/delete
- Genre associations

### 5. Filtering & GraphQL  
- Endpoint to filter movies by genre
- GraphQL schema + resolver implementation

### 6. Deployment Prep  
- Environment config
- Database migrations and seed scripts
- Docker environment orchestration

Each section of this project was developed in its own feature branch before being merged into `main`, following a professional Git workflow.

---

## 📂 Folder Structure

go-react-movie-app/
├── backend/ # Go API
│ ├── cmd/
│ ├── internal/
│ ├── handlers/
│ ├── models/
│ └── main.go
├── frontend/ # React app
│ ├── src/
│ ├── public/
│ └── package.json
├── docker-compose.yml # Local development stack
└── README.md

yaml
Copy code

---

## 📦 Environment Setup

To run this project locally:

1. Clone the repo  
   ```bash
   git clone https://github.com/YOUR_USERNAME/go-react-movie-app.git
    
Start the dev stack

bash
Copy code
docker-compose up
Navigate:

Frontend: http://localhost:3000

Backend API: http://localhost:8000

Make sure:

Docker Desktop is installed

Environment variables are configured