# Responsive Landing Page 🚀

This project is a **Responsive Landing Page** built using:
- **React.js (Frontend)**
- **Node.js + Express.js (Backend)**

## Features
✅ Interactive navigation bar (changes color on scroll & hover)  
✅ Responsive design (mobile-friendly)  
✅ Fixed position navbar (visible on all pages)  
✅ Smooth scrolling & animations  

---

## Installation & Setup

### 1. Clone or Extract Project
```bash
unzip responsive-landing.zip
cd responsive-landing
```

### 2. Setup Backend (Express.js)
```bash
cd server
npm install
node server.js
```
Server will run on `http://localhost:5000`

### 3. Setup Frontend (React.js)
```bash
cd ../client
npm install
npm start
```
Frontend will run on `http://localhost:3000`

---

## Folder Structure
```
responsive-landing/
│── client/    # React Frontend
│── server/    # Node + Express Backend
│── README.md  # Setup Guide
```

Enjoy building your landing page 🎉


---

## 🚀 Deployment Guide

### 🌐 Frontend (React.js)
You can deploy the frontend on **Vercel** or **Netlify**.

#### Deploy on Vercel:
1. Install Vercel CLI (if not installed)
   ```bash
   npm i -g vercel
   ```
2. Inside the `client` folder, run:
   ```bash
   npm run build
   vercel deploy
   ```

#### Deploy on Netlify:
1. Inside the `client` folder, run:
   ```bash
   npm run build
   ```
2. Upload the `build/` folder to Netlify.

---

### ⚙️ Backend (Node + Express)
You can deploy the backend on **Render** or **Heroku**.

#### Deploy on Render:
1. Push your project to GitHub.
2. Go to [Render](https://render.com/).
3. Create a new Web Service → Connect GitHub repo.
4. Add **Build Command**:
   ```bash
   npm install
   ```
5. Add **Start Command**:
   ```bash
   node server.js
   ```

#### Deploy on Heroku:
1. Install Heroku CLI
   ```bash
   npm i -g heroku
   ```
2. Inside the `server` folder, run:
   ```bash
   git init
   heroku create
   git add .
   git commit -m "Deploy backend"
   git push heroku master
   ```
3. Heroku will give you a live URL for your backend.

---

### 🔗 Connecting Frontend & Backend
- After deploying backend, copy the deployed API URL (e.g., `https://myapp.onrender.com`).
- In your React frontend (`client/src/...`), replace any `http://localhost:5000` with the deployed backend URL.
- Rebuild (`npm run build`) and redeploy frontend.

🎉 Your project will now be fully online!
