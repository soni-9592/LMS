# 🛠️ Library Management System - Backend

This is the **backend API** for a simple Library Management System, built using **Python (Flask)** and **MongoDB**. It provides RESTful endpoints for user registration, login, and book management (add/search/borrow/return).

---

## 🚀 Features

- 🔐 User registration & login with secure password hashing
- 📚 Add, list, and search books
- 📖 Borrow and return books with session tracking
- ⏱️ 1-hour session timeout for security
- 🧾 View borrowed books
- ⚙️ CORS enabled for frontend integration

---

## 🧑‍💻 Tech Stack

- **Backend**: Flask, Flask-CORS
- **Database**: MongoDB
- **Security**: Werkzeug password hashing
- **Session Handling**: Flask's built-in session

---
---

## ⚙️ Installation & Setup

### 🧱 Prerequisites

- Python 3.7+
- MongoDB installed and running locally on default port (`mongodb://localhost:27017`)
- `pip` installed

---

### 🪄 Steps

```bash
# 1. Clone the repo
git clone https://github.com/your-username/LMS.git
cd LMS/backend

# 2. Create a virtual environment (optional)
python -m venv venv
source venv/bin/activate    # or venv\Scripts\activate on Windows

# 3. Install dependencies
pip install -r requirements.txt

# 4. Run the backend server
python app.py


