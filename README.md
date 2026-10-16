# 🛣️ Smart Road Maintenance System

A full-stack web platform designed for digital civic infrastructure management. Citizens can report road maintenance issues (such as potholes, damaged dividers, or broken shoulder edges), while administrators can review, assign, and track complaint statuses in real time.

🚀 **Live Demo:** https://smart-road-maintenance-puce.vercel.app

---

## ✨ Features

- **User Authentication:** Secure user signup and login powered by JWT.
- **Issue Reporting:** Submit road maintenance complaints with zone mapping and status tracking.
- **Admin Console:** Dashboard for reviewing pending complaints and updating resolution statuses.
- **Responsive Interface:** Clean UI built with React and Vite.

---

## 🛠️ Tech Stack

- **Frontend:** React.js, Vite, Tailwind CSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB Atlas (Cloud)
- **Deployment:** Vercel (Frontend), Render (Backend)

---

## 📁 Repository Structure

```text
Smart-road-maintenance/
├── frontend/     # React + Vite application
└── server/       # Node.js + Express API server
---
Backend (/server/.env)
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret

Frontend (/frontend/.env)
VITE_API_URL=[https://smart-road-maintenance.onrender.com/api](https://smart-road-maintenance.onrender.com/api)

💻 Local Setup

Clone the repository: git clone [https://github.com/Shivam-k27/Smart-road-maintenance.git](https://github.com/Shivam-k27/Smart-road-maintenance.git)
cd Smart-road-maintenance

Start Backend Server:
cd server
npm install
npm start

Start Frontend Application:
cd ../frontend
npm install
npm run dev

