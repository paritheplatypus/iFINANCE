💼 iFINANCE – Web-Based Accounting System
A modern, full-stack financial management system with secure role-based access, real-time reporting, double-entry bookkeeping, and a clean dashboard UI — built for both realism and learning.
🚀 Tech Stack
Frontend
Backend
Database
Features
EJS, CSS3
Express.js
MySQL
Auth, Sessions, CSV Export
Bootstrap
Node.js
MySQL2
Reports, Transactions, Charts
📂 Project Structure
pgsql
Copy
Edit
├── app.js                    # Main server file
├── routes/                   # Express routes (auth, dashboard, etc.)
│   ├── auth.js
│   ├── dashboard.js
│   ├── reports.js
│   └── transactions.js
├── views/                    # EJS templates
│   ├── admin.ejs
│   ├── user.ejs
│   └── transactions.ejs
├── public/                   # Static assets (CSS, logo, JS)
│   └── styles.css
├── config/
│   └── db.js                 # MySQL database connection
├── package.json
└── README.md
👥 User Roles
Feature
Admin
Non-Admin
User Login
✅
✅
Change Own Password
✅
✅
Register New Users
✅
❌
Manage (View/Edit/Delete) Users
✅
❌
Create Transactions
❌
✅
View Financial Reports
❌
✅
Manage Chart of Accounts
❌
✅
Access Account Group Hierarchy
❌
✅
Export Transactions (CSV)
❌
✅
Admin: Only manages user accounts — login, registration, view, edit, and delete users.
Non-Admin: Handles all core accounting operations, including transactions, reports, account group hierarchy, chart of accounts, and exporting data.
🧪 Sample Logins
Role
Username
Password
Admin
admin
admin123
User
user
admin123
🔧 Run Locally
bash
Copy
Edit
# 1. Install dependencies
npm install

# 2. Start the app
node app.js

# 3. Visit in browser
http://localhost:3000
📤 Bonus Features
✅ Floating help assistant for user onboarding
✅ Transaction export to CSV
✅ Profit & Loss and Trial Balance with visuals
✅ Password expiry logic (configurable)
✅ Clean and modern UI with Bootstrap & gradients
📦 Build as .exe (optional)
Use pkg to bundle:
bash
Copy
Edit
npm install -g pkg
pkg .
Produces a standalone executable: ifinance.exe
🧠 Designed For Learning
This system is designed to reflect real-world accounting logic while remaining lightweight and easy to understand.
✅ MVC structure
✅ SQL normalization
✅ Secure session handling
✅ Reusable UI components
📜 License
MIT — open to use, remix, and improve.
👤 Author
Developed by Group 10
CS4320 Software Engineering Project · University of Missouri
2025

Patel, Pari Hirenkumar (MU-Student)
​
Yi, Claire (MU-Student)
​
# 💼 iFINANCE – Web-Based Accounting System

A modern, full-stack financial management system with secure role-based access, real-time reporting, double-entry bookkeeping, and a clean dashboard UI — built for both realism and learning.

---

## 🚀 Tech Stack

| Frontend   | Backend     | Database | Features                       |
|------------|-------------|----------|--------------------------------|
| EJS, CSS3  | Express.js  | MySQL    | Auth, Sessions, CSV Export     |
| Bootstrap  | Node.js     | MySQL2   | Reports, Transactions, Charts  |

---

## 📂 Project Structure

```
├── app.js                    # Main server file
├── routes/                   # Express routes (auth, dashboard, etc.)
│   ├── auth.js
│   ├── dashboard.js
│   ├── reports.js
│   └── transactions.js
├── views/                    # EJS templates
│   ├── admin.ejs
│   ├── user.ejs
│   └── transactions.ejs
├── public/                   # Static assets (CSS, logo, JS)
│   └── styles.css
├── config/
│   └── db.js                 # MySQL database connection
├── package.json
└── README.md
```

---

## 👥 User Roles

| Feature                           | Admin | Non-Admin |
|----------------------------------|:-----:|:---------:|
| View/Create/Delete Users         | ✅    | ❌        |
| Create Transactions              | ✅    | ✅        |
| View Financial Reports           | ✅    | ✅        |
| Change Own Password              | ✅    | ✅        |
| Manage Chart of Accounts         | ✅    | ❌        |
| Access Account Group Hierarchy   | ✅    | ❌        |
| Export Transactions (CSV)        | ✅    | ✅        |

---

## 🧪 Sample Logins

| Role  | Username | Password  |
|-------|----------|-----------|
| Admin | admin    | admin123  |
| User  | user     | admin123  |

---

## 🔧 Run Locally

```bash
# 1. Install dependencies
npm install

# 2. Start the app
node app.js

# 3. Visit in browser
http://localhost:3000
```

---

## 📤 Bonus Features

- ✅ Floating help assistant for user onboarding
- ✅ Transaction export to CSV
- ✅ Profit & Loss and Trial Balance with visuals
- ✅ Password expiry logic (configurable)
- ✅ Clean and modern UI with Bootstrap & gradients

---

## 📦 Build as .exe (optional)

Use [`pkg`](https://github.com/vercel/pkg) to bundle:

```bash
npm install -g pkg
pkg .
```

> Produces a standalone executable: `ifinance.exe`

---

## 🧠 Designed For Learning

This system is designed to reflect real-world accounting logic while remaining lightweight and easy to understand.

- ✅ MVC structure
- ✅ SQL normalization
- ✅ Secure session handling
- ✅ Reusable UI components

---

## 📜 License

MIT — open to use, remix, and improve.

---

## 👤 Author

Developed by **Group 10**
CS4320 Software Engineering Project · University of Missouri  
2025
