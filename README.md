# 🏦 Biometric ATM System with Face Verification

A secure and interactive ATM simulation system using email-password login and facial recognition for enhanced user authentication.

Built using **Flask (Python)**, **HTML/CSS/JavaScript**, **OpenCV**, and **face_recognition**.

---

## 🚀 Features

- 🔐 Secure Login with Email & Password
- 👁️ Face Recognition-based Verification using Webcam
- 🧾 ATM Dashboard:
  - View Profile
  - Deposit and Withdraw Money
  - Transaction History
  - Edit Profile
  - Change PIN
- 🧠 SQLite + SQLAlchemy ORM for user and transaction data
- 📷 Face match powered by `face_recognition` and OpenCV

---

## 📁 Folder Structure

ATM_System/
├── app.py
├── models.py
├── requirements.txt
├── static/
│ ├── script.js
│ └── styles.css
│ └── uploads/ # Stores user profile photos
├── templates/
│ ├── index.html # Start page
│ ├── login.html # Email/Password login
│ ├── signup.html # User registration
│ ├── facebox.html # Webcam face verification
│ └── atm.html # Main dashboard
├── database.db
└── README.md


---

## 🛠️ Setup Instructions

  # 1. Clone the repository

  git clone https://github.com/GyanPrakash-30/ATM_System.git
 
  cd ATM_System

  # 2. Create and activate virtual environment (optional but recommended)

  python -m venv venv
  source venv/bin/activate  # Windows: venv\Scripts\activate

  # 3. Install dependencies

  # ✅ Dependencies
   -> Flask
   -> Flask-Cors
   -> Flask-SQLAlchemy
   -> Werkzeug
   -> Pillow
   -> face_recognition
   -> opencv-python
   
   pip install -r requirements.txt
   
  Or install manually if needed:
    pip install flask flask_sqlalchemy flask_cors pillow opencv-python face_recognition
    If face_recognition fails, install cmake and dlib first.

### ▶️ Running the App
   python app.py

### 🧠 How It Works

 1. Signup: User registers with profile photo
 2. Login: User enters email & password
 3. Facebox: After successful login, user is redirected to webcam verification
 4. Face Match: Captured face is compared with stored image using face_recognition
 5. Success: User enters ATM dashboard with full access

### Screenshots

 # -📥 Login Page
   ![image](https://github.com/user-attachments/assets/275d7d83-adbd-450c-b0b8-519f661e0dfc)

 # -📸 Face Verification
   ![image](https://github.com/user-attachments/assets/e29e3056-26bd-4b8e-8abe-0841e5e06618)

# -🏦 ATM Dashboard
  ![image](https://github.com/user-attachments/assets/c72809ad-ecf6-451d-92eb-589758912f1f)


MIT License © 2026 Pandegokul

  

