🔐 SecureScribe
SecureScribe is a privacy-focused mail encryption app that allows users to securely send and receive emails. It uses strong encryption techniques to ensure that messages remain confidential and tamper-proof. The app integrates with Gmail and leverages App Passwords for secure access.

✨ Features

📧 Gmail inbox integration using App Passwords

🧠 User-friendly registration and login system

🧾 Store and manage user credentials securely

🌐 React + Flask based full-stack web application

✅ Protected routes for logged-in users only

🚀 Tech Stack
Frontend: Reacta

Backend: Flask, Flask-CORS

Email Integration: Gmail App Passwords, IMAP/SMTP

Encryption: Python's cryptography or RSA modules

Storage: SQLite or JSON-based file system

📦 Installation
1. Clone the repository
bash
Copy
Edit
git clone https://github.com/yourusername/securescribe.git
cd securescribe
2. Install backend dependencies
bash
Copy
Edit
cd backend
pip install -r requirements.txt
3. Install frontend dependencies
bash
Copy
Edit
cd ../frontend
npm install
4. Run the app
Backend (Flask):

bash
Copy
Edit
cd backend
python app.py
Frontend (React):

bash
Copy
Edit
cd ../frontend
npm start
🛠️ Usage
Register with your email and a Gmail App Password (for inbox access).

Log in securely.

Access your encrypted inbox.

Send or receive encrypted messages.

💡 App Passwords are required due to Gmail's OAuth restrictions. You can generate one from your Google Account Settings.

📂 Project Structure
css
Copy
Edit
securescribe/
│
├── backend/
│   ├── app.py
│   ├── routes/
│   ├── utils/
│   └── database/
│
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   └── App.js
│
├── README.md
└── requirements.txt
✅ Future Enhancements

📎 File attachment encryption

📱 Mobile responsive UI

🔐 OAuth-based login and using rsa-aes for encryption and decryption

📊 Dashboard analytics


