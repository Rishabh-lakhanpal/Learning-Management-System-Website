# SkillNest - Django Learning Management System

SkillNest is a web-based Learning Management System (LMS) built using Django. It allows students to browse courses, view content, and manage their learning schedule. Admins can manage courses, authors, payments, and more through the Django admin panel.

---

## 🔧 Tech Stack

- **Backend:** Django 5.x
- **Frontend:** HTML5, CSS3, Bootstrap 5, JavaScript
- **Database:** SQLite (default)
- **Payment Gateway:** Razorpay Integration
- **Others:** Crispy Forms, Razorpay, Bootstrap Pagination

---

## 📦 Features

### 🎓 Student Side
- Homepage with featured content
- Course listings and filtering
- Course pagination
- Contact form
- Registration & Login system
- My Courses dashboard

### 🔐 Admin Side
- Django Admin for:
  - Authors, Categories, Lessons
  - Payments, Users, Courses
- Add/Edit/Delete full content

---
## 🚧 Project Status

This project is currently a work-in-progress.  
Basic functionalities are in place, but some parts (like data display, layout polishing, and user flow fixes) are under development.  
Improvements and fixes will be made in the upcoming updates.

## 🚀 How to Run Locally

```bash
# 1. Clone the repository

# 2. Install dependencies
pip install -r requirements.txt

# 3. Run migrations
python manage.py migrate

# 4. Create superuser
python manage.py createsuperuser

# 5. Start the server
python manage.py runserver
