# 📌 Vedant Task Manager 

A full-featured task management application designed for individuals and teams to organize, track, and collaborate on tasks effectively.

---

## 🚀 Features

1. **User Dashboard** – View assigned tasks, track progress, and get task insights.  
2. **Task Management** – Create, update, and track tasks with due dates and priorities.  
3. **Automated Status Updates** – Task status changes automatically based on the checklist.  
4. **Team Collaboration** – Assign tasks to multiple users and track completion.  
5. **Priority & Progress Tracking** – Categorize tasks by priority and monitor completion levels.  
6. **Task Report Downloads** – Export task data for analysis and tracking.  
7. **Attachments Support** – Add and access task-related file links easily.  
8. **Mobile Responsive UI** – Seamless experience on desktop, tablet, and mobile.  
9. **Intuitive Navigation** – Clean sidebar menu for quick access to tasks and dashboard.  

---

## 🛠️ Tech Stack

- **Frontend:** React.js, Tailwind CSS 
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB  
- **Authentication:** JWT

---

## 🛠️ Setup Instructions

### 1. Clone the Repository
   ```bash

   cd Task-Manager-mern
```
---

#### 📁 Project Structure

```
root/
│
├── backtend/               # React frontend
│
├── frontend/Task-Manager   # Express backend with mongoDB
│
├── profile pics/           # Express backend with mongoDB
│
└── README.md
```

---

### 2. Install Dependencies

#### Server (Backend)

```bash
cd backend
npm install
npm install jsonwebtoken
npm install mongoose
```

#### Client (Frontend)

```bash
cd ../frontend
cd Task-Manager
npm install

```
---


🔐 Roles

Admin and member roles are stored in MongoDB using the `role` field:

```js
role: "admin"
role: "member"
```

👨‍💼 Admin:
✅ Can manage tasks
✅ Can manage team members
✅ Can access dashboard data
✅ Can generate and manage reports

👨‍💻 Member:
✅ Can view assigned tasks
✅ Can update task checklist progress

🔑 Demo Login Credentials

Admin invite token : 123456 , if any one want to be Admin 

👑 Admin Login

📧 Email: [vedantadmin@gmail.com](mailto:vedantadmin@gmail.com)
🔒 Password: 12345678

👤 User Login

📧 Email: [kartik@gmail.com](mailto:kartik@gmail.com)
🔒 Password: 12345678

📧 Email: [sumit@gmail.com](mailto:sumit@gmail.com)
🔒 Password: 12345678


## 🔧 Environment Variables

Create a `.env` file in the `backend`.

### Example `.env` for `backend`:

```
PORT=5000
MONGO_URI=your_mongodb_connection_string
WT_SECRET=mysecretkey
ADMIN_INVITE_TOKEN=123456
```
---
## 🧪 Run the App Locally

### Run Backend

```bash
cd backend
npm run dev
```

### Run Frontend

In a new terminal:

```bash
cd frontend
cd Task-Manager
npm run dev
```

Open your browser and go to `http://localhost:5173`

---

