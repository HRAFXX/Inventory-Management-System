# 📦 Inventory Management System

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Built with Flask](https://img.shields.io/badge/Built%20with-Flask-blue.svg)](https://flask.palletsprojects.com/)
[![Database: MongoDB](https://img.shields.io/badge/Database-MongoDB-brightgreen.svg)](https://www.mongodb.com/)
[![Frontend: Bootstrap](https://img.shields.io/badge/Frontend-Bootstrap-purple.svg)](https://getbootstrap.com/)

## 🧾 Overview

Welcome to the **Inventory Management System**—a sleek, web-based app built to help you stay on top of your stock game. Whether you’re selling cupcakes or computer parts, this tool helps track products, transactions, and generates reports like a boss.

---

## 🚀 Features

- 🔄 **Add / Edit / Delete Products**
- 🛒 **Track Sales & Purchases**
- 📊 **Generate Inventory Reports**
- 👤 **User Authentication**
- 💻 **Bootstrap-Powered UI**

---

## 🛠️ Tech Stack

- **Backend**: Flask (Python)
- **Database**: MongoDB
- **Frontend**: Bootstrap + Jinja2 Templates
- **Authentication**: Flask-Login (optional)

---

## 📸 Screenshots

> _Coming soon! Add screenshots in the `images/` folder to show off your UI._

- `images/dashboard.png` — Your dashboard.
- `images/product_management.png` — Product view.

---

## ⚙️ Getting Started

### 1. Clone the Repo

`
git clone https://github.com/HRAFXX/Inventory-Management-System.git
cd Inventory-Management-System `

### 2. Create a Virtual Environment
`
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate`

### 3. Install the Requirements
`bash
pip install -r requirements.txt`

### 4. Set Up Environment Variables
Create a .env file in the root and add:
`bash
FLASK_APP=app.py
FLASK_ENV=development
SECRET_KEY=your_secret_key
MONGO_URI=your_mongodb_connection_string`

### 5. Run the App
`bash
flask run`

Then open your browser and go to:
👉 http://localhost:5000

### 🗂️ Project Structure
Inventory-Management-System/
├── static/
│   ├── css/
│   └── js/
├── templates/
│   ├── base.html
│   ├── dashboard.html
│   └── ...
├── app.py
├── requirements.txt
├── .env.example
└── README.md
### 🧪 Testing
Add your testing strategy here if needed.
For now, good ol’ manual testing will do the trick! 🧼🖱️

### 🤝 Contributing
Feel like making this cooler? Fork the repo, make your changes, and open a pull request.

PRs are welcome, especially with:

✨ New Features

🐛 Bug Fixes

💅 UI Improvements

### 📄 License
This project is licensed under the MIT License.
Feel free to use, share, and modify!

### 🌟 A Final Word
This is a great beginner-to-intermediate full-stack project. You can expand it with:

📷 Barcode scanning

🧩 REST API support

🔐 User roles & permissions

📑 PDF or Excel report exports


 
