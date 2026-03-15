🚀 Flask Web Application

A simple Flask-based web application that demonstrates backend development using Python, Flask, and SQL database integration.

This project implements backend routing, database configuration, and a basic web interface to handle user interaction through a browser.

📌 Project Overview

This application was built to understand the core concepts of backend development with Flask, including:

Application routing

Database configuration

SQL schema management

Python backend logic

Basic frontend integration

The project demonstrates how a Flask server connects with a database and serves HTML pages to users.

🛠️ Technologies Used
Backend

🐍 Python

🌶️ Flask

Database

🗄️ SQL

SQLite / MySQL (depending on configuration)

Frontend

🌐 HTML

Tools

Git

GitHub

VS Code

📂 Project Structure
Flask_App/
│
├── app.py              # Main Flask application
├── config.py           # Configuration settings for database and app
├── schema.sql          # Database schema and table structure
├── index.html          # Frontend HTML page
├── requirements.txt    # Python dependencies
│
└── README.md           # Project documentation
⚙️ Installation & Setup

Follow these steps to run the project locally.

1️⃣ Clone the Repository
git clone https://github.com/chandunandarapu/Flask_App.git
2️⃣ Navigate to the Project Folder
cd Flask_App
3️⃣ Create Virtual Environment (Recommended)
python -m venv venv

Activate it:

Windows

venv\Scripts\activate

Mac / Linux

source venv/bin/activate
4️⃣ Install Dependencies
pip install -r requirements.txt
5️⃣ Setup Database

Run the schema file to create tables.

Example:

sqlite3 database.db < schema.sql

(or use MySQL depending on config settings)

6️⃣ Run the Application
python app.py
7️⃣ Open in Browser
http://127.0.0.1:5000
📖 Key Concepts Implemented

This project demonstrates:

Flask Application Structure

How to organize a Flask backend application.

Example:

Routing

Request handling

Server execution

Database Integration

Using SQL schema to create and manage database tables.

Example:

Table creation

Data storage

Query execution

💡 Learning Outcomes

Through this project I learned:

Flask application structure

Backend routing with Python

Database schema design

SQL database integration

Basic frontend-backend communication

📬 Contact

If you'd like to connect or discuss backend development:

📧 Email
chandunandarapu01@gmail.com

🔗 LinkedIn
https://linkedin.com/in/chandunandarapu

💻 GitHub
https://github.com/chandunandarapu

⭐ Support

If you found this project useful, consider giving it a star ⭐ on GitHub.
