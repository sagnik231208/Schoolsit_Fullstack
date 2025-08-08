 # 🏫 SchoolSite – A Full-Stack School Website Built with Django

Welcome to **SchoolSite**, a powerful and modern full-stack school website project built using **Django** (backend) and **HTML, CSS, JavaScript** (frontend). This project aims to provide students, teachers, and administrators with a secure and intuitive web platform for managing academic activities, communication, and content.

---

## 👥 Created By

**Sagnik Mukherjee**
**Shubhoshree Ghosh**
*H.M. Education Centre*

---

## 🌐 Live Demo

> *Coming soon* – To deploy this project online, see the deployment section below.

---

## 🎯 Purpose

This project is designed for **schools** to manage key operations like:

* Student & teacher profiles
* Dashboards
* Uploading and viewing results
* Publishing notices and news
* Contacting the institution
* Showcasing achievements, events, and galleries

---

## 🚀 Tech Stack

| Layer      | Technology                                   |
| ---------- | -------------------------------------------- |
| Frontend   | HTML5, CSS3, JavaScript                      |
| Backend    | Python 3 + Django (v4.x or above)            |
| Styling    | Custom CSS / Bootstrap / Tailwind (optional) |
| Database   | SQLite (default), PostgreSQL-ready           |
| Templates  | Django Templating Engine                     |
| Deployment | Optional: Railway, Heroku, Render, etc.      |

---

## 📁 Project Structure

The full directory tree can be found in the `create_school_website.bat` scaffold, but here are the main components:

```
SchoolSite_FullStack/
├── config/        # Django settings and routing
├── core/          # Home, about, FAQ
├── users/         # Login, registration, profile management
├── dashboard/     # Dashboards for students and teachers
├── news/          # News & events
├── gallery/       # Image & video gallery
├── notices/       # School notices
├── results/       # Academic results
├── contact/       # Contact form
├── api/           # Optional REST API (Django REST Framework)
├── templates/     # Global HTML templates (base, navbar, etc.)
├── static/        # Global static files (CSS, JS, images)
├── media/         # Uploaded files (avatars, gallery images)
└── utils/          # Helper functions and tools
```

---

## 🧪 Features

### ✅ Public Pages

* Homepage, About, FAQ
* News and announcements
* Contact form with backend mail support
* Photo and event gallery

### 🔐 Authentication System

* User registration, login, logout
* Role-based access (students, teachers, staff)
* Profile editing
* Avatar upload support

### 🧑‍🏫 Student/Teacher Dashboards

* See personalized announcements and results
* Upload/download documents
* Notice board view

### 📊 Academic Results Module

* Admins upload results
* Students view/download their marksheets securely

### 📢 Notice & News Board

* Display school notices, upcoming events, and important circulars

### 📨 Contact Form

* Built-in form with email support
* Sends queries directly to school's designated email

---

## ⚙️ Setup Instructions

### Prerequisites

* Python 3.9 or higher
* Git (optional)
* Virtualenv (recommended)

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/schoolsite.git
cd SchoolSite_FullStack
```

### 2. Create and Activate Virtual Environment

```bash
python -m venv venv
venv\Scripts\activate      # Windows
# OR
source venv/bin/activate   # Linux/macOS
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Configure Environment

Create a `.env` file:

```env
DEBUG=True
SECRET_KEY=your-secret-key
ALLOWED_HOSTS=127.0.0.1,localhost
```

### 5. Run Migrations

```bash
python manage.py migrate
```

### 6. Create Superuser

```bash
python manage.py createsuperuser
```

### 7. Run the Server

```bash
python manage.py runserver
```

Visit: [http://127.0.0.1:8000](http://127.0.0.1:8000)

---

## 🤪 Testing the App

Try logging in with your superuser account and:

* Visit `/admin` to manage models.
* Visit `/dashboard/` for role-based panels.
* Try uploading news, results, etc.

---

## 🛠️ Deployment (Optional)

You can deploy to any platform that supports Django:

* **Render** – Free + easy deployment with database support
* **Railway.app** – Modern PaaS, auto deploy from GitHub
* **Heroku** – Still useful with Heroku CLI

---

## 🤝 Contributing

If you'd like to contribute, fork the repo and submit a pull request.

---

## 📜 License

This project is open-source and licensed under the [MIT License](LICENSE).

---

## 🙏 Credits

This full-stack Django project was created with love by:

* **Sagnik Mukherjee**
* **Shubhoshree Ghosh**

Under the banner of **H.M. Education Centre**.

Special thanks to the open-source community and Django docs.