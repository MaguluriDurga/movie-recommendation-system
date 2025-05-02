### 📄 `README.md`

```markdown
# MERN Stack Project

This is a MERN (MongoDB, Express.js, React, Node.js) stack project that includes a full-stack web application with separate frontend and backend components.

## 📁 Project Structure

```

/client     # React frontend
/server     # Node.js + Express backend

````

## 🚀 Getting Started

### Prerequisites

Make sure you have the following installed:

- Node.js (v14+)
- npm or yarn
- MongoDB (local or Atlas)

---

## 🖥️ Running the Project Locally

### 1. Clone the repository

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
````

---

### 2. Start the Backend (Node + Express)

```bash
cd server
npm install
# Optional: Create a .env file for MongoDB URI and other secrets
npm start
```

By default, the backend runs at: `http://localhost:5000`

---

### 3. Start the Frontend (React)

Open a new terminal:

```bash
cd client
npm install
npm start
```

By default, the frontend runs at: `http://localhost:3000`

---

## 🛠️ Tech Stack

* **Frontend**: React
* **Backend**: Node.js, Express.js
* **Database**: MongoDB (Mongoose)

---

## 📦 Environment Variables

Create a `.env` file in the `/server` folder and add:

```env
MONGO_URI=your-mongodb-uri
PORT=5000
```

---

