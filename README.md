📝 To-Do List (Flask Web App)

A simple To-Do List web application built using Flask, a lightweight Python web framework. It allows users to add, view, update, and delete tasks.

🚀 Features

✅ Add new tasks
🗑️ Delete tasks
🔁 Update tasks
🕒 Task timestamps (date added)
📦 Uses SQLite for database storage
🖥️ Basic HTML + CSS interface (Jinja templating)
🛠️ Tech Stack

Backend: Python, Flask
Frontend: HTML, CSS, Jinja2
Database: SQLite (via SQLAlchemy ORM)
📸 Preview



🧑‍💻 Getting Started

Prerequisites
Make sure you have Python 3 installed.

Installation
Clone the repository:
git clone https://github.com/philip-thomas-12/to_do_list_flask.git
cd to_do_list_flask
Create a virtual environment (optional but recommended):
python3 -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
Install dependencies:
pip install -r requirements.txt
Run the app:
python app.py
Open your browser and go to:
http://localhost:5000
📁 Project Structure

to_do_list_flask/
│
├── app.py                  # Main Flask app
├── requirements.txt        # Python dependencies
├── static/                 # CSS, images, etc.
│   └── style.css
├── templates/              # HTML templates (Jinja2)
│   ├── base.html
│   └── index.html
└── README.md               # This file
⚙️ Customization

To improve the UI, you can add more styling in static/style.css.
To switch databases (e.g., MySQL or MongoDB), update the SQLALCHEMY_DATABASE_URI in app.py accordingly.
🧠 Future Improvements

✅ Task update functionality
🔒 User login system
🎨 Better UI/UX with Bootstrap or Tailwind CSS
☁️ Host on platforms like Render or Vercel
📃 License

This project is licensed under the MIT License. Feel free to use, modify, and share!