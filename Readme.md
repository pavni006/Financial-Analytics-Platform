# Financial Analytics Platform 💹

**A High-Performance Full-Stack Ecosystem for Financial Data Management and Real-Time Insights.**

[![Node.js](https://img.shields.io/badge/Backend-Node.js-green)](https://nodejs.org/) 
[![PostgreSQL](https://img.shields.io/badge/Database-PostgreSQL-blue)](https://www.postgresql.org/)
[![React](https://img.shields.io/badge/Frontend-React.js-61DAFB)](https://reactjs.org/)
[![JWT](https://img.shields.io/badge/Security-JWT-gold)](https://jwt.io/)

---

## 🚀 Overview
This platform functions as a robust financial engine, **orchestrating** complex data flows between a React-driven interface and a high-concurrency Node.js backend. By **structuring** a relational database with strategic indexing, the system ensures sub-second query execution for massive datasets involving multi-category expenses and monthly financial summaries.

## 🛠 Technical Core

### 1. High-Performance API Layer
* **Orchestrated** a RESTful API ecosystem using Express.js to facilitate high-frequency CRUD operations for complex budget management.
* **Unified** frontend-backend communication through asynchronous logic, ensuring a non-blocking user experience during heavy data fetching.

### 2. Database Schema & Query Performance
* **Structured** a PostgreSQL relational model utilizing strategic indexing on category and date fields to **streamline** reporting throughput.
* **Formulated** complex SQL queries to aggregate financial data, providing instantaneous monthly and category-wise spending analysis.

### 3. Security & Access Control
* **Hardened** the application perimeter by **executing** a JWT-based authentication layer with Bcrypt password hashing.
* **Enforced** strict role-based access controls (RBAC) to protect sensitive user financial records and prevent unauthorized API access.

### 4. Data Visualization & UI
* **Visualized** multi-dimensional spending trends using **Chart.js**, translating raw financial records into actionable real-time insights.
* **Crafted** a responsive React interface that maintains 100% data consistency across diverse financial modules.

## 📊 Performance Benchmarks
* **Query Latency:** Reduced data retrieval times for complex reports through B-Tree indexing on primary PostgreSQL entities.
* **Security Standards:** Applied industry-standard salt rounds for Bcrypt hashing to ensure high resistance against brute-force attacks.

## ⚙️ Installation & Setup

### Clone the repository
```bash
git clone https://github.com/pavni006/Financial-Analytics-Platform.git
cd Financial-Analytics-Platform
```

### Backend Setup 
```bash
cd backend
npm install
npm run start
```

### Create a .env file
```bash
DB_USER=your_db_user
DB_HOST=localhost
DB_PASS=your_db_password
DB_PORT=5432
JWT_SECRET=your_secret
```

### Frontend Setup
```bash
cd frontend
npm install
npm run dev
```

Backend runs on http://localhost:5000

Frontend runs on http://localhost:5173

---

## 📌 API Overview
- POST /users/signup – Register user
- POST /users/login – Login user
- POST /expenses – Add expense
- GET /expenses – List expenses
- POST /budgets – Set monthly budget
