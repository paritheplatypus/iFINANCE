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
![image](https://github.com/user-attachments/assets/8ac788b3-32d0-46b0-9b4d-7827426bbab3)


---

## 👥 User Roles

| Feature                           | Admin | Non-Admin |
|----------------------------------|:-----:|:---------:|
| View/Create/Delete Users         | ✅    | ❌       |
| Create Transactions              | ❌    | ✅       |
| View Financial Reports           | ❌    | ✅       |
| Change Own Password              | ✅    | ✅       |
| Manage Chart of Accounts         | ❌    | ✅       |
| Access Account Group Hierarchy   | ❌    | ✅       |
| Export Transactions (CSV)        | ❌    | ✅       |

---

## 🧪 Sample Logins

| Role  | Username | Password  |
|-------|----------|-----------|
| Admin | admin    | admin     |
| User  | test     | test      |

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

## 📦 Run as .exe (optional)

Navigate to "C:\CS4320\Group10_iFINANCEAPP\dist\ifinance Setup 1.0.0.exe" and double-click to run.

