# 📝 To-Do App

Welcome to **To-Do App**! This project is a simple and efficient to-do list application built with **Angular** for the frontend, **NestJS** for the backend, and **SQLite** as the database. This project was developed as part of a homework assignment during an interview, and it demonstrates the ability to build a full-stack application within a limited timeframe.

## 🚀 Features

- **Task Management**: Create, update, and delete tasks.
- **Task Sorting and Filtering**: Organize tasks.
- **Responsive UI**: Optimized for both desktop and mobile devices.
- **Authentication**: Secure login.
  
## 🛠 Tech Stack

- **Frontend**: [Angular](https://angular.io/)
- **Backend**: [NestJS](https://nestjs.com/)
- **Database**: [SQLite](https://www.sqlite.org/)

## 📦 Installation

### Prerequisites

Make sure you have the following installed:

- **Node.js** (v14 or above)
- **npm** (v6 or above)
  
### Clone the Repository

```bash
git clone https://github.com/EvaldasP/todo-app.git
cd todo-app
git submodule update --init
```
### Install Dependencies

```bash
cd todo-be
git checkout main
git pull
npm install
```
```bash
cd todo-fe
git checkout main
git pull
npm install
```

## ▶️ Running the Application
```bash
cd todo-be
npm run start:dev
```
```bash
cd todo-fe
ng serve
```
Database already setuped (for testing only)
## Hardcoded Users
```bash
username: 'alice' password: 'password1'
username: 'bob' password: 'password2'
```

## 📚 API Documentation
API documentation for the backend (NestJS) is generated using Swagger.
After running the backend, you can view the API docs at:

```bash
http://localhost:3000/api
```
## 🛠 Future Improvements
- Registration (In Progress)
- Pagination.
