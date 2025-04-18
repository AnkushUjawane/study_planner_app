# 📚 Study Planner & Collaborative Timetable App

A full-stack web application that helps students manage their study schedules, track tasks, and collaborate with peers in real-time using a shared timetable.

🧠 About the Project -<br>
Study Planner App is designed to improve student productivity and time management. With features like customizable timetables, personal to-do lists, and real-time group collaboration, users can better plan, monitor, and adjust their study routines efficiently.

<h3>🛠️ Tech Stack</h3>

| Layer          | Tech                  | Purpose                                 |
|----------------|-----------------------|-----------------------------------------|
| Frontend       | React.js              | UI, Timetable, Task Management          |
| Backend (API)  | Flask (Python)        | User Auth, Timetable & Task APIs        |
| Backend (RT)   | Node.js + Socket.IO   | Real-time collaboration features        |
| Database       | SQLite/PostgreSQL     | User data, tasks, timetables            |

<h3>🔑Feature</h3>
👤 User Authentication
 - Register / Login
 - JWT based secure access

🗓️ Study Planner
 - Daily/Weekly calendar
 - Drag & drop timetable (coming soon)
 - Color-coded subject blocks

✅ Task Manager
 - Add / Edit / Delete tasks
 - Set priorities and deadlines
 - Task completion tracking

👥 Collaborative Groups
 - Create / Join study groups
 - Real-time shared timetable
 - Socket.IO powered live updates

🔔 Notifications (Planned)
 - Task deadline reminders
 - Group activity alerts

<h3>🚀 Getting Started</h3>
Prerequisites
 - Node.js
 - Python 3
 - pip
 - npm

<h4>Clone the repository</h4>
 - git clone https://github.com/yourusername/study-planner-app.git
 - cd study-planner-app

1. Setup Flask backend
 - cd flask-backend
 - pip install -r requirements.txt
 - python app.py

2. Setup Node.js backend
 - cd ../node-backend
 - npm install
 - node server.js

3. Setup React frontend
 - cd ../client
 - npm install
 - npm start

<h3>🌟 Contributions</h3>
 - This project is open for contributions! You can:
 - Report bugs
 - Suggest features
 - Submit PRs for improvements