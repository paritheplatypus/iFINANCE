# iFINANCE

📊 **iFINANCE System — Web-Based Accounting Platform**
A full-featured, role-based financial management system built with Node.js, Express, MySQL, and EJS, designed to simulate a real-world accounting application with users, accounts, transactions, and reporting.

🔧 **Technologies Used**
Backend: Node.js, Express
Frontend: EJS Templates, Bootstrap CSS
Database: MySQL
Encryption: bcryptjs
Session Management: express-session
Packaging: pkg (for Windows .exe)

🧩 **System Overview**
This system is built according to a detailed UML diagram and supports:
🧑‍💼 Administrator and 🧑‍💻 Non-Admin Users (via iFINANCEUser inheritance)
🔐 Secure login with password encryption
💳 Double-entry transaction system
📁 Group and category-based account management
📊 Auto-generated financial reports (Trial Balance, P&L, Balance Sheet)

📂 **Folder Structure**
php
Copy
Edit
├── app.js
├── launcher.js          # Used for packaging into .exe
├── public/              # Static files (styles.css, logo.png)
├── routes/              # Express route files (auth.js, dashboard.js, reports.js)
├── views/               # EJS templates (login, dashboard, reports, user, admin)
├── config/
│   └── db.js            # MySQL connection config
├── package.json

👥 **User Roles**

Feature	Admin	Non-Admin
View/Create/Delete Users	      ✅	  ❌
Create Transactions	            ✅	  ✅
Access All Reports	            ✅	  ❌
Change Own Password	            ✅	  ✅
Manage Chart of Accounts	      ✅	  ❌
Access Account Group Hierarchy	✅	  ❌

🧪 **Sample Login Credentials**
Admin: admin / admin123
User: user / admin123

Password hash generated with bcrypt.

⚙️ **Run Locally**
bash
Copy
Edit
npm install
node app.js
Then visit: http://localhost:3000

💡 **Compile as Executable (Optional)**
bash
Copy
Edit
pkg .
Creates ifinance.exe — double-click to launch app and browser.

📈 **Bonus Features You Can Add**
Chart.js dashboards (P&L and trial balance visualized)
Built-in chatbot for accounting help
User audit trail
CSV export for reports
Password expiry notifications

🧠 **Designed for Realism**
Fully matches UML class model
Implements database inheritance
Follows MVC architecture
Includes full CRUD operations
Uses real accounting logic

**© 2025 Pari Patel**
