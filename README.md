# QuickChat

A full-stack real-time chat application built with **React (Vite)** on the frontend and **Node.js + Express** on the backend.
It supports authentication, user profiles, and real-time messaging with a clean UI.

---

## 🚀 Features

* User authentication (login, signup, profile management)
* Real-time chat interface
* Sidebar with online users & conversations
* Responsive design with reusable React components
* Context API for global state management
* Vite for fast frontend builds
* Express backend for handling API requests

---

## 📂 Project Structure

```
QuickChat/
│── client/          # Frontend (React + Vite)
│   ├── src/
│   │   ├── assets/  # Images, icons, logos
│   │   ├── components/  # Reusable UI components
│   │   ├── context/     # Auth & Chat Context
│   │   ├── pages/       # Login, Home, Profile pages
│   │   ├── App.jsx
│   │   └── main.jsx
│   ├── index.html
│   ├── vite.config.js
│   └── package.json
│
│── server/          # Backend (Node.js + Express)
│   ├── server.js    # Main server entry
│   └── package.json
│
└── README.md
```

---

## 🛠️ Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/Priyanshu745/QuickChat.git

```

### 2. Setup the frontend

```bash
cd client
npm install
npm run dev   # Runs frontend in development mode
npm run build # Builds production-ready frontend
```

### 3. Setup the backend

```bash
cd server
npm install
node server.js
```

---

## ⚡ Deployment (Render)

For **Render** deployment:

* **Build Command:**

  ```bash
  cd client && npm install && npm run build
  ```

* **Publish Directory:**

  ```
  client/dist
  ```

* **Backend:** Deploy `server/` separately as a **Web Service**.

---

## 📜 Scripts

### Frontend (Client)

* `npm run dev` → Start dev server
* `npm run build` → Build production app
* `npm run preview` → Preview production build

### Backend (Server)

* `node server.js` → Run server
* (Optional) add `nodemon` for hot reload


