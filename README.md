# iFINANCE – Web-Based Accounting System

A modern, full-stack financial management system with secure role-based access, real-time reporting, double-entry bookkeeping, and a clean dashboard UI — built for both realism and learning.

---

## Tech Stack

| Frontend   | Backend     | Database | Features                       |
|------------|-------------|----------|--------------------------------|
| EJS, CSS3  | Express.js  | MySQL    | Auth, Sessions, CSV Export     |
| Bootstrap  | Node.js     | MySQL2   | Reports, Transactions, Charts  |

---

## Project Structure

├── app.js # Main server file
├── routes/ # Express routes (auth, dashboard, etc.)
│ ├── auth.js
│ ├── dashboard.js
│ ├── reports.js
│ └── transactions.js
├── views/ # EJS templates
│ ├── admin.ejs
│ ├── user.ejs
│ └── transactions.ejs
├── public/ # Static assets (CSS, logo, JS)
│ └── styles.css
├── config/
│ └── db.js # MySQL database connection
├── package.json
└── README.md

yaml
Copy
Edit

---

## User Roles

| Feature                           | Admin | Non-Admin |
|------------------------------------|:-----:|:---------:|
| View/Create/Delete Users           |  Yes  |    No     |
| Create Transactions                |  Yes  |   Yes     |
| View Financial Reports             |  Yes  |   Yes     |
| Change Own Password                |  Yes  |   Yes     |
| Manage Chart of Accounts           |  Yes  |    No     |
| Access Account Group Hierarchy     |  Yes  |    No     |
| Export Transactions (CSV)          |  Yes  |   Yes     |

---

## Sample Logins

| Role   | Username | Password  |
|--------|----------|-----------|
| Admin  | admin    | admin123  |
| User   | user     | admin123  |

---

## How to Run Locally

```bash
# 1. Install dependencies
npm install

# 2. Start the app
node app.js

# 3. Visit in browser
http://localhost:3000
##Bonus Features
Floating help assistant for user onboarding

Transaction export to CSV

Profit & Loss and Trial Balance with visuals

Password expiry logic (configurable)

Clean and modern UI with Bootstrap and gradients

##Build as .exe (optional)
Use pkg to bundle:

bash
Copy
Edit
npm install -g pkg
pkg .
This will produce a standalone executable: ifinance.exe

##Designed For Learning
This system is designed to reflect real-world accounting logic while remaining lightweight and easy to understand.

MVC structure

SQL normalization

Secure session handling

Reusable UI components

##License
MIT — open to use, remix, and improve.

##Author
Developed by Group 10
CS4320 Software Engineering Project · University of Missouri
2025
