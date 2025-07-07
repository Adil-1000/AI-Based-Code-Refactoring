
# ✅ Code Refactorer Project – Requirements & Setup Guide

This document lists all the required tools, libraries, and packages you need to run the Code Refactorer project on your system. It also includes step-by-step instructions for setting up the backend, frontend, and database.

---

## 🔧 1. Tools You Need to Install

Make sure these are installed on your computer:

- **Python** (version 3.9 or above)
- **Node.js** (version 18 or above)
- **MongoDB** (you can install locally or use MongoDB Atlas)
- **Git** (for cloning the project)
- **VS Code** (recommended editor)

---

## 🧠 2. Backend (Python + FastAPI + ML Model)

### 📁 Navigate to the backend folder:
```bash
cd backend
```

### 🛠️ Create and activate virtual environment:
```bash
python -m venv venv
source venv/bin/activate      # Windows: venv\Scripts\activate
```

### 📦 Install required Python libraries:
```bash
pip install -r requirements.txt
```

### 📄 Key Python Libraries:
- `fastapi`: For building backend API
- `uvicorn`: To run the FastAPI server
- `transformers`: For loading the ML model (e.g., CodeLLaMA, StarCoder)
- `torch`: For running the model
- `pymongo`: To connect with MongoDB

---

## 🌐 3. Frontend (Next.js + React + TypeScript)

### 📁 Navigate to the frontend folder:
```bash
cd frontend
```

### 📦 Install required Node.js packages:
```bash
npm install
```

### ▶️ Start the frontend server:
```bash
npm run dev
```

This runs your web app at: http://localhost:3000

---

## 🗄️ 4. Database (MongoDB)

- Make sure MongoDB is running on your system.
- Use [MongoDB Compass](https://www.mongodb.com/products/compass) to visualize your data.
- Backend automatically stores user code and optimized output.

---

## ✅ 5. Quick Recap of Commands

```bash
# Clone project
git clone https://github.com/your-username/code-refactorer.git

# Backend setup
cd backend
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
uvicorn api:app --reload

# Frontend setup
cd ../frontend
npm install
npm run dev
```

---

You are now ready to run and test the Code Refactorer system locally.
