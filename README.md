# 📝 TaskMate - A Simple Task Management App

TaskMate is a simple and responsive task management web app that allows users to:

- ✅ Create new tasks
- 📌 Mark tasks as complete (future scope)
- ❌ Delete tasks
- 💾 Store tasks on a backend server using Node.js

---

## 🚀 Tech Stack

### 🔹 Frontend:
- React.js
- HTML, CSS, JavaScript
- Responsive Design (Media Queries / Tailwind CSS)

### 🔹 Backend:
- Node.js
- Express.js
- In-memory task storage (can be extended to MongoDB)

---

## 📁 Project Folder Structure
taskmate/
├── client/ # React frontend
│ └── App.js # Main frontend logic
├── server/ # Node.js backend
│ └── index.js # Express backend server
└── README.md # Project documentation

yaml file name

---

## ⚙️ How to Run the Project

### ✅ Step 1: Start Backend Server

```bash
cd server
node index.js

Server runs on: http://localhost:5000

✅ Step 2: Start Frontend App
bash
Copy
Edit
cd client
npm start
App runs on: http://localhost:3000

🌐 API Routes (Backend)
Method	Route	Description
GET	/api/tasks	Get all tasks
POST	/api/tasks	Add a new task
DELETE	/api/tasks/:id	Delete task by ID

💡 Future Scope
Add checkboxes to mark tasks complete

Use MongoDB for persistent storage

Add login/signup functionality

🤝 Author
Dhanraj Rajendra Sonawane

yaml
Copy
Edit

---

## 🔄 2. Git Setup and GitHub पर Upload करने के Step

### ✅ Step 1: Git Initialize

```bash
cd E:\WebProject\taskmate
git init
✅ Step 2: Files Add करें Git में
bash
Copy
Edit
git add .
✅ Step 3: First Commit करो
bash
Copy
Edit
git commit -m "Initial TaskMate project setup"
✅ Step 4: GitHub पर Repository बनाओ
जाओ: https://github.com/new

Repo name डालो: taskmate

Create Repository दबाओ

✅ Step 5: Local Project GitHub से जोड़ो
bash
Copy
Edit
git remote add origin https://github.com/dhanrajsonawane/taskmate.git
git branch -M main
git push -u origin main


bash
Copy
Edit
git remote remove origin
git remote add origin https://github.com/dhanrajsonawane/taskmate.git

