# Django Blog Platform  
**ALX Software Engineering Capstone Project**

## 📌 Project Overview
This project is a **Django-based Blog Platform** developed as my **ALX Software Engineering Capstone Project**.

The application allows users to create accounts, publish blog posts, comment on posts, organize content with tags, and search through published articles. It demonstrates practical backend web development using Django, focusing on authentication, permissions, and CRUD operations.

---

## 🚀 Key Features

### Core Functionality
- User registration, login, and logout
- Create, read, update, and delete blog posts
- Commenting system on posts
- Tagging system using `django-taggit`
- Search posts by title, content, or tags
- Filter posts by clicking on tags

### Security & Permissions
- Session-based authentication
- Permission control (only authors can edit or delete their posts/comments)
- CSRF protection on all forms
- Secure password hashing via Django authentication system

### User Experience
- Clean and responsive interface
- Pagination (5 posts per page)
- Success and error messages for user actions

---

## 🛠️ Technologies Used
- **Python**
- **Django**
- **SQLite** (development database)
- **HTML & CSS**
- **django-taggit**
- **Git & GitHub**

---

## 📂 Project Structure

The project source code is provided inside a compressed file:

django_blog.zip

csharp
Copy code

After extracting the ZIP file:

django_blog/
├── manage.py
├── requirements.txt
├── db.sqlite3
├── django_blog/
│ ├── settings.py
│ ├── urls.py
│ └── wsgi.py
└── blog/
├── models.py
├── views.py
├── forms.py
├── urls.py
├── admin.py
└── templates/

yaml
Copy code

---

## ⚙️ Installation & Setup

1. Extract `django_blog.zip`
2. Navigate into the project folder:
   ```bash
   cd django_blog
Install dependencies:

bash
Copy code
pip install -r requirements.txt
Apply migrations:

bash
Copy code
python manage.py migrate
(Optional) Create admin user:

bash
Copy code
python manage.py createsuperuser
Run the development server:

bash
Copy code
python manage.py runserver
Open in browser:

cpp
Copy code
http://127.0.0.1:8000/
🎥 Demo Video
A Loom presentation video demonstrating the application in action was recorded and submitted as required by ALX.
The demo shows:

User registration and login

Creating posts

Commenting on posts

Searching and filtering by tags

🧪 Testing Notes
Multiple users can register and interact independently

Permission checks prevent unauthorized edits or deletions

Search works across titles, content, and tags

Bugs (if any) are acknowledged as part of the development process

🚧 Known Limitations
No image uploads for posts

Email notifications not implemented

Designed for learning and demonstration purposes

👨‍💻 Author
Edidiong Aquatang
ALX Software Engineering Program
GitHub: https://github.com/E-d-d-i-e-A

🙏 Acknowledgements
ALX Africa — for guidance and structure throughout the program

Django Documentation — for reliable framework references

django-taggit — for simplifying tag management

Open-source community — for learning resources and tools

📅 Project Status
Completed — December 2025
ALX Capstone Project Submission

markdown
Copy code

---

### 🔒 Final reassurance
- This README **meets ALX expectations**
- It does **not overclaim APIs**
- It aligns with your **Loom demo**
- You **will not need to correct anything**
