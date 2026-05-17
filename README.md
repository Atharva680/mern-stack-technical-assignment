
# 🌌 StoreRate — AI Powered Store Rating Platform

> A futuristic MERN Stack web application where users can discover stores, submit ratings, manage analytics, and interact with a beautifully animated modern dashboard experience.

---

# ✨ Features

## 👨‍💻 Admin Dashboard
- Manage Users
- Manage Stores
- Platform Analytics
- Role-Based Access Control
- Dynamic Filtering & Sorting
- Secure JWT Authentication
- Dashboard Statistics

---

## 🛒 User Features
- Signup/Login
- Browse Registered Stores
- Search Stores
- Submit Ratings ⭐
- Modify Ratings
- Responsive Dashboard
- View Overall Store Ratings

---

## 🏪 Store Owner Features
- Store Analytics Dashboard
- Customer Rating Insights
- Average Store Ratings
- Statistics Overview

---

# ⚡ Modern UI Features

✅ Plasma Wave WebGL Effects  
✅ Interactive Border Glow  
✅ Glassmorphism UI  
✅ Smooth Animations  
✅ Responsive Mobile Design  
✅ 3D Styled Components  
✅ Futuristic Dark Theme  
✅ Animated Dashboards  

---

# 🧠 Tech Stack

<div align="center">

| Frontend | Backend | Database | Styling |
|----------|----------|----------|----------|
| React 19 | Node.js | PostgreSQL | Tailwind CSS |
| TypeScript | Express.js | SQL | Custom Animations |
| Vite | JWT Auth | UUID | WebGL Effects |

</div>

---

# 🏗️ Project Architecture

```bash
StoreRate/
│
├── src/
│   ├── components/
│   ├── pages/
│   ├── assets/
│   ├── hooks/
│   └── styles/
│
├── backend/
│   ├── controllers/
│   ├── routes/
│   ├── middleware/
│   ├── database/
│   └── utils/
│
└── README.md
````

---

# 🌍 Live Demo

<div align="center">

<a href="YOUR_DEPLOYMENT_LINK">
<img src="https://img.shields.io/badge/🚀%20LIVE%20DEMO-000?style=for-the-badge&logo=vercel&logoColor=white"/>
</a>

<a href="YOUR_PORTFOLIO_LINK">
<img src="https://img.shields.io/badge/🌐%20PORTFOLIO-111?style=for-the-badge&logo=firefox&logoColor=white"/>
</a>

</div>

---

# 📸 Preview

<div align="center">

<img src="https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake-dark.svg"/>

</div>

---

# 🔐 Security Features

* JWT Authentication
* bcrypt Password Hashing
* Role-Based Access Control
* SQL Injection Prevention
* Secure API Architecture
* Environment Variable Security
* Input Validation

---

# 🛢️ Database Schema

```mermaid
erDiagram

USERS ||--o{ RATINGS : gives
STORES ||--o{ RATINGS : receives
USERS ||--o{ STORES : owns

USERS {
  uuid id
  string name
  string email
  string password
  string role
}

STORES {
  uuid id
  string name
  string address
  uuid owner_id
}

RATINGS {
  uuid id
  int rating
  uuid user_id
  uuid store_id
}
```

---

# 🚀 Installation Guide

## 📥 Clone Repository

```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPO.git
```

---

## 📦 Frontend Setup

```bash
npm install
npm run dev
```

---

## ⚙️ Backend Setup

```bash
cd backend

npm install

npm run dev
```

---

# 🌍 Environment Variables

Create `.env` inside backend folder:

```env
DATABASE_URL=postgresql://postgres:password@localhost:5432/store_rating
JWT_SECRET=your_secret_key
PORT=5000
NODE_ENV=development
```

---

# 📊 API Endpoints

## 🔑 Authentication

```http
POST   /api/auth/login
POST   /api/auth/signup
POST   /api/auth/update-password
```

---

## 👥 Users

```http
POST   /api/users
GET    /api/users
GET    /api/users/:id
DELETE /api/users/:id
```

---

## 🏪 Stores

```http
POST   /api/stores
GET    /api/stores
GET    /api/stores/:id
DELETE /api/stores/:id
```

---

## ⭐ Ratings

```http
POST   /api/ratings
GET    /api/ratings/store/:storeId
GET    /api/ratings/stats/overview
```

---

# 🎨 UI Design

<div align="center">

| Dashboard                                | Analytics                                | Ratings                                  |
| ---------------------------------------- | ---------------------------------------- | ---------------------------------------- |
| ![](https://via.placeholder.com/400x220) | ![](https://via.placeholder.com/400x220) | ![](https://via.placeholder.com/400x220) |

</div>

---

# 📈 GitHub Analytics

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=YOUR_USERNAME&show_icons=true&theme=tokyonight"/>

<img height="180em" src="https://github-readme-streak-stats.herokuapp.com/?user=YOUR_USERNAME&theme=tokyonight"/>

<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_USERNAME&layout=compact&theme=tokyonight"/>

</div>

---

# ⚡ Contribution Workflow

```bash
Fork 🍴
↓
Clone 📥
↓
Create Branch 🌿
↓
Commit Changes 💻
↓
Push 🚀
↓
Create Pull Request 🔥
```

---

# 🧩 Future Enhancements

* 🤖 AI Review Analysis
* 📱 Mobile Application
* 🔔 Real-time Notifications
* 📊 AI Graph Analytics
* 🌍 Multi-language Support
* 💬 AI Chatbot Integration

---

# 👨‍💻 Developer

<div align="center">

<img src="https://avatars.githubusercontent.com/u/9919?s=200&v=4" width="120" style="border-radius:50%"/>

# Abhiram MK

### 🚀 Full Stack Developer | AI/ML Enthusiast | MERN Developer

</div>

---

# 🌐 Connect With Me

<div align="center">

<a href="https://github.com/YOUR_USERNAME">
<img src="https://img.shields.io/badge/GitHub-000?style=for-the-badge&logo=github"/>
</a>

<a href="https://linkedin.com/in/YOUR_LINKEDIN">
<img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin"/>
</a>

<a href="mailto:YOUR_EMAIL">
<img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail"/>
</a>

<a href="https://twitter.com/YOUR_USERNAME">
<img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter"/>
</a>

</div>

---

# ⭐ Support

If you like this project, give it a ⭐ on GitHub and share it with others!

---

<div align="center">

# 💫 “Code. Create. Innovate. Repeat.”

<img src="https://capsule-render.vercel.app/api?type=waving&height=180&color=0:0072ff,25:00c6ff,50:24243e,75:302b63,100:0f0c29&section=footer"/>

</div>
```
