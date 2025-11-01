# 🧾 Todo List App

A simple **task management application** built with **Node.js**, **Express**, and **PostgreSQL**, following the **MVC architecture**.  
It allows users to create, view, update, and delete daily tasks efficiently.

---

## 📌 Features

- ✅ Add new todos
- ✏️ Edit existing tasks
- ❌ Delete completed or unwanted todos
- 📋 View all tasks with completion status
- 🧱 Clean **MVC folder structure**
- 🔒 Secure SQL queries using parameterized statements

---

## 🛠 Tech Stack

- **Backend**: Node.js, Express
- **Database**: PostgreSQL
- **Query Tool / ORM**: \`pg\`
- **Environment Management**: \`dotenv\`
- **Architecture**: MVC (Model–View–Controller)

---

## 🧩 Folder Structure

\`\`\`
todo-app-postgres-practice/
├── controllers/ # Handles request logic
├── models/ # Database queries
├── routes/ # API endpoints
├── config/ # DB connection setup
├── public/ # Static files (if any)
├── views/ # Templates (if using EJS or similar)
├── .env # Environment variables
└── server.js # App entry point
\`\`\`

---

## ⚙️ Setup & Run

### 1️⃣ Clone the repository

\`\`\`bash
git clone https://github.com/aditya-rbj/todo-app-postgres-practice.git
cd todo-app-postgres-practice
\`\`\`

### 2️⃣ Install dependencies

\`\`\`bash
npm install
\`\`\`

### 3️⃣ Set up the .env file

\`\`\`env
PORT=3000
DATABASE_URL=postgres://user:password@localhost:5432/todo_db
\`\`\`

### 4️⃣ Run the server

\`\`\`bash
npm start
\`\`\`

Server runs on → [http://localhost:3000](http://localhost:3000)

---

## 🧠 Learning Highlights

- Hands-on practice with **PostgreSQL CRUD operations**
- Understanding **one-to-many relationships** between users and tasks
- Applying **MVC design pattern**
- Using **Express routing** and **PostgreSQL integration**

---

## 📚 Future Enhancements

- 🔐 Add user authentication
- 🗓 Filter tasks by due date or priority
- ☁️ Deploy on Render / Vercel / Railway
