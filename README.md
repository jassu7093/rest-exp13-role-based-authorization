# 🧪 REST API Experiment 13 — Role-Based Authorization (Admin vs User Access)

## 📘 Objective
To implement **Role-Based Authorization** in a REST API using **Node.js**, **Express**, **MongoDB**, and **JWT**, ensuring that specific routes can only be accessed by users with appropriate roles (e.g., Admin vs User).

---

## 🧠 Learning Outcomes
- Assign and manage **user roles** during registration.  
- Protect routes based on **user roles** using middleware.  
- Learn how **JWT payloads** carry role information for access control.  
- Restrict access to admin-only endpoints.

---

## ⚙️ Tools & Technologies
- **Node.js**
- **Express.js**
- **MongoDB / Mongoose**
- **bcrypt**
- **jsonwebtoken**
- **dotenv**
- **Postman**

---

## 🏗️ Folder Structure
rest-exp13-role-based-authorization/
│
├── server.js
├── models/
│ └── User.js
├── routes/
│ ├── authRoutes.js
│ └── adminRoutes.js
├── middleware/
│ ├── authMiddleware.js
│ └── roleMiddleware.js
├── .env
├── .env.example
├── package.json
└── README.md

---

## 🚀 Setup Instructions
```bash
# Step 1: Initialize Node project
npm init -y

# Step 2: Install dependencies
npm install express mongoose bcrypt jsonwebtoken dotenv

# Step 3: Create folders
mkdir models routes middleware
touch server.js models/User.js routes/authRoutes.js routes/adminRoutes.js middleware/authMiddleware.js middleware/roleMiddleware.js .env .env.example

# Step 4: Run the server
node server.js
```
## output

<img width="1066" height="776" alt="rest_13 (1)" src="https://github.com/user-attachments/assets/8038ce9a-5239-4ad4-9146-fa6558205338" />
<img width="1071" height="776" alt="rest_13 (3)" src="https://github.com/user-attachments/assets/64fb81ed-60ca-4948-923f-476da04194c3" />
<img width="1084" height="792" alt="rest_13 (2)" src="https://github.com/user-attachments/assets/e7973a03-b541-416b-bc28-d359754c96ff" />



