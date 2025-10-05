# TodosApp 📝

A web application to manage a to-do list (tasks) built with Django (backend) and HTML, CSS & JavaScript (frontend).

---

## 📦 Tech Stack

- Backend: Django (Python)  
- Frontend: HTML, CSS, JavaScript  
- Database: SQLite (for development)  
- Version Control: Git & GitHub  

---

## 📂 Project Structure

todosapp/
├── todosapp/ # Django project folder (settings, urls, wsgi)
├── tasks/ # Django app for to-do items (models, views, templates)
├── templates/ # HTML templates
├── static/ # CSS
├── manage.py
├── requirements.txt
└── README.md

yaml
Copy code

---

## 🛠️ Setup & Installation

1. Clone the repo  
   ```bash
   git clone https://github.com/adelana107/Todosapp.git
   cd Todosapp
Create a virtual environment

bash
Copy code
python -m venv env
Activate it

Windows: env\Scripts\activate

macOS / Linux: source env/bin/activate

Install dependencies

bash
Copy code
pip install -r requirements.txt
Run migrations

bash
Copy code
python manage.py makemigrations
python manage.py migrate
Create a superuser (optional)

bash
Copy code
python manage.py createsuperuser
Start the development server

bash
Copy code
python manage.py runserver
Open your browser at:

cpp
Copy code
http://127.0.0.1:8000/
📌 Usage
Add new to-do items

Mark tasks as complete/incomplete

Edit or delete tasks

View list of tasks

(Optional) Filter or search tasks

🧪 Testing & Debugging
Use:

bash
Copy code
python manage.py test
Check console logs, check browser DevTools (Console/Network) for frontend issues.

🚀 Deployment Notes
Set DEBUG = False in settings

Use a production database (PostgreSQL, MySQL)

Serve static files (via collectstatic, WhiteNoise, or CDN)

Use a WSGI server (Gunicorn) behind a web server (e.g. Nginx)

Configure ALLOWED_HOSTS

👤 Author
Adelana Oluwafunmibi
GitHub: adelana107
