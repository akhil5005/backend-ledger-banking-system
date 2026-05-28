````md
# Backend Ledger Banking Transaction System

## Overview

A secure backend banking ledger transaction system developed using Node.js, Express.js, MongoDB, and JWT Authentication. This project manages banking transactions, user authentication, ledger entries, and transaction history through REST APIs.

---

# Features

- User Registration & Login
- JWT Authentication & Authorization
- Secure Password Hashing
- Banking Ledger Management
- Credit & Debit Transactions
- Transaction History APIs
- MongoDB Database Integration
- RESTful API Architecture
- Error Handling Middleware
- Environment Variable Configuration

---

# Tech Stack

## Backend
- Node.js
- Express.js

## Database
- MongoDB
- Mongoose

## Authentication
- JWT (JSON Web Token)
- bcrypt.js

## Tools
- Postman
- Git & GitHub
- VS Code

---


````

---

# Installation & Setup

## Clone Repository

```bash
git clone https://github.com/akhil5005/backend-ledger-banking-system.git
```

## Move Into Project Folder

```bash
cd backend-ledger-banking-system
```

## Install Dependencies

```bash
npm install
```

## Create Environment File

Create a `.env` file in the root directory.

```env
PORT=3000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

## Start Server

```bash
npm start
```

or

```bash
node server.js
```

---

## Live Backend URL:
https://backend-ledger-banking-system.onrender.com/

---

# API Functionalities

## Authentication APIs

* User Registration
* User Login
* JWT Token Generation

## Banking APIs

* Add Transaction
* Debit Transaction
* Credit Transaction
* Fetch Transaction History
* Ledger Management

---

# Database Screenshots

## Users Collection
<img width="1925" height="916" alt="usersRegistartionDatabase" src="https://github.com/user-attachments/assets/175e86df-099d-49ac-b983-5e5f7397470e" />

## Transactions Collection
<img width="1925" height="919" alt="TransactionsDatabase" src="https://github.com/user-attachments/assets/d154f1f6-176b-4ab8-960d-0aedeb00be17" />

## Ledger Collection
<img width="1925" height="1021" alt="LedgerDatabase" src="https://github.com/user-attachments/assets/8f2ce444-7b63-4cdb-91c1-7f6021c4d932" />

## Accounts Database
<img width="1902" height="731" alt="accountDatabase" src="https://github.com/user-attachments/assets/87b5a5a5-07c6-4369-801f-1275b98bd204" />

## Token Blacklists Database
<img width="1925" height="731" alt="tokenBlacklistsDatabase" src="https://github.com/user-attachments/assets/58555579-3b26-41d5-8fbd-4a1cf4609b8f" />

---

# Postman API Testing

Take screenshots of:

## Register API

<img width="1924" height="832" alt="usersRegistration" src="https://github.com/user-attachments/assets/3a9a6b69-0558-49da-9732-6568776719f0" />

## Login API

<img width="1911" height="887" alt="login" src="https://github.com/user-attachments/assets/a9d7630d-a3f2-4273-822a-a54a0cf95ea9" />

## Create Account API

<img width="1924" height="901" alt="Account" src="https://github.com/user-attachments/assets/28421421-298f-4c7d-8d58-b6da985c20db" />

## Add Transaction API

<img width="1925" height="961" alt="Add Transaction API" src="https://github.com/user-attachments/assets/75ed1a08-21a4-4989-96da-bb6bcb323f94" />

## Logout API

<img width="1925" height="857" alt="tokenBlacklistsAPI" src="https://github.com/user-attachments/assets/1280d578-2480-4a4c-a605-d89767162824" />

## Server Running 

<img width="901" height="247" alt="ServerRunningTerminal" src="https://github.com/user-attachments/assets/e9730fc2-4003-4e0c-bff1-fea21fd26500" />

```bash
Server is running on port 3000
Server is connected to MongoDB 
```

## Folder Structure

<img width="387" height="516" alt="projectStructure" src="https://github.com/user-attachments/assets/4ca62320-530c-4759-9980-df23abddde2c" />

---

# Security Features

* JWT Authentication
* Password Encryption using bcrypt
* Protected Routes
* Environment Variable Security
* Middleware-Based Error Handling

---

# Learning Outcomes

Through this project, I learned:

* Backend Development
* REST API Design
* MongoDB Integration
* Authentication & Authorization
* JWT Security
* Express Middleware
* Database Schema Design
* GitHub Project Management

---

# Author

## AKHIL MITTAL

* B.E. Computer Engineering
GitHub: https://github.com/akhil5005

---

```
```
