# School Management System API

A Node.js + Express.js + MySQL based backend project to manage school data.

## 🚀 Features

- Add new schools
- Store school data in MySQL database
- Fetch schools sorted by proximity using latitude & longitude
- REST API architecture
- Live deployed backend

## 🛠 Tech Stack

- Node.js
- Express.js
- MySQL
- Railway (Database Hosting)
- Render (Backend Hosting)

## 📌 API Endpoints

### Add School

POST `/addSchool`

Sample Body:

```json
{
  "name": "ABC School",
  "address": "Delhi",
  "latitude": 28.61,
  "longitude": 77.20
}

List Schools

GET /listSchools?latitude=28.61&longitude=77.20

Returns schools sorted by nearest distance.

🌐 Live Demo

https://school-management-system-8edn.onrender.com

📂 GitHub Repository

https://github.com/Sukanya428/school-management-system

👩‍💻 Author

Sukanya Rao