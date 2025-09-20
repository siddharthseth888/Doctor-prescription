# Doctor-Prescription

**Doctor-Prescription** is a full-stack web application built using the **MERN** stack (MongoDB, Express.js, React.js, Node.js) for managing doctor appointments and generating prescriptions. It has separate frontend and backend codebases and supports user authentication, doctor and patient roles, appointment scheduling, and prescription management.

---

## 🚀 Features

- User authentication (login/signup)  
- Role-based access: Doctors & Patients  
- Patients can book appointments with Doctors  
- Doctors can view appointments and generate prescriptions  
- Frontend built with React.js for responsive UI  
- Backend API built with Express.js & Node.js  
- MongoDB for data storage  

---

## 🛠 Prerequisites

Make sure you have the following installed:

- Node.js (v14 or above recommended)  
- npm (Node package manager)  
- MongoDB running locally or remote connection string  
- Git  

---

## 📦 Installation & Setup

Follow these steps to set up the project locally:


## 1. Clone the repository
```bash
git clone https://github.com/siddharthseth888/Doctor-prescription.git
cd Doctor-prescription
```

## 2. Backend setup
```bash
cd backend
npm install
```

## 2a. Create environment variables
*Create a .env file in backend folder with contents like:*\
*MONGODB_URI=<your_mongodb_connection_string>*\
*JWT_SECRET=<your_jwt_secret>*\
*PORT=5000*

## 3. Start backend server
```bash
npm start
```

## In a new terminal, go back to root
```bash
cd ../frontend
npm install
```
## 4. Frontend configuration (if needed)
##### If frontend needs API base URL, create a .env or config file, for example:
#####   REACT_APP_API_URL=http://localhost:5000

## 5. Start frontend
```
npm start
```

## 📍 Usage

Once both backend and frontend are running:

Open your browser and go to http://localhost:3000 (or whatever port frontend is running on).

Sign up / log in as patient or doctor.

Patients: Browse doctors, book appointments.

Doctors: View appointments, generate prescription forms or records.

## 🔧 Scripts

##Here are some useful npm scripts in both frontend & backend:

```npm install``` — install all dependencies

```npm start ```— start the server (backend or frontend)

(Optionally) ```npm run dev``` — if there is a script for development hot-reloading

## 🔁 Directory Structure
```bash
Doctor-prescription/
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── app.js or server.js
│   ├── package.json
│   └── .env (you’ll create)
├── frontend/
│   ├── src/
│   ├── public/
│   ├── package.json
│   └── .env (you’ll configure if needed)
└── README.md
```

## ⚙️ Notes

Always make sure MongoDB is running before starting the backend.

If using a cloud MongoDB provider (like MongoDB Atlas), whitelisting of IPs / CORS configuration might be needed.

Make sure the JWT secret is kept private (don’t commit .env to version control).

For production, handy to build and serve frontend with production optimizations.

## 🤝 Contributing

Contributions are welcome! Feel free to:

Fork the repository

Create a new branch for your changes

Submit pull requests

## 📝 License & Author

Author: Siddharth Seth

GitHub: [siddharthseth888](https://github.com/siddharthseth888)
