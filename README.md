# 📝 MiniBlog Project

A simple full-stack blogging platform built with **Node.js (Express)** for backend and a **Vanilla/React frontend** for UI.

**🚩🚩This is a back-end training project and I had no role in the front-end.**

---

## 📁 Project Structure

miniblog/

├── back-end/ → REST API (Node.js, Express, MongoDB)

├── front-end/ → User Interface (HReact)


---

## 🚀 Features


- User authentication (JWT)
- Password hashing (bcrypt)
- CRUD for blog posts
- Protected routes
---

## 🛠️ Tech Stack

- Node.js
- Express.js
- MongoDB
- JWT
- HTML / CSS / JavaScript (React)

---

## ⚙️ Installation

### 1. Clone repo

```
git clone <https://github.com/tahadeh2010/miniBlog>

cd miniblog
```
### 2. Backend setup 
```
cd back-end
npm install
npm run dev
```
Create .env file:
```
PORT=5000
JWT_SECRET=your_secret
MONGO_URI=your_db_url
```
### 3. Frontend setup
```
cd front-end
npm install
npm start
```
---
## Notes
Frontend is only for testing and demonstration
Backend is fully independent REST API
You can use Postman for testing endpoints
