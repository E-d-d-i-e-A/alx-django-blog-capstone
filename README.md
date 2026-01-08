# Django Blog Platform  
**ALX Software Engineering – Capstone Project**

## 📌 Overview
The Django Blog Platform is a full-featured web application built with Django as part of the ALX Software Engineering Capstone Project. The project demonstrates core backend development skills such as user authentication, CRUD operations, relational database modeling, permissions, form handling, tagging, and search functionality.

The application allows users to create accounts, publish blog posts, comment on posts, organize content with tags, and search for posts. Permission rules ensure that only content authors can edit or delete their own posts.

---

## 🎯 Project Objectives
- Build a complete Django web application from scratch
- Implement secure user authentication and authorization
- Apply CRUD operations using Django class-based views
- Demonstrate real-world features such as search, tagging, and permissions
- Present a working application through a Loom demo video

---

## 🚀 Features

### Core Features
- User registration, login, and logout
- User profile management
- Create, read, update, and delete blog posts
- Commenting system for blog posts
- Tag posts using multiple tags
- Filter posts by tag
- Search posts by title, content, or tags
- Pagination (5 posts per page)

### Security & Permissions
- Session-based authentication
- Only post authors can edit or delete their posts
- Only comment authors can edit or delete their comments
- CSRF protection on all forms
- Secure password hashing using Django authentication system

### User Experience
- Clean and responsive interface
- Success and error feedback messages
- Simple and intuitive navigation

---

## 🛠️ Technologies Used
- **Backend:** Django  
- **Database:** SQLite (development)  
- **Authentication:** Django built-in authentication  
- **Tagging:** django-taggit  
- **Frontend:** HTML, CSS, JavaScript  
- **Version Control:** Git & GitHub  

---

## 📂 Project Structure
django_blog/ ├── django_blog/ │   ├── settings.py │   ├── urls.py │   └── wsgi.py ├── blog/ │   ├── models.py │   ├── views.py │   ├── forms.py │   ├── urls.py │   ├── admin.py │   ├── templates/ │   └── static/ ├── manage.py ├── requirements.txt └── README.md
Copy code

---

## 🔧 Installation & Setup

### Prerequisites
- Python 3.8 or higher
- pip
- Git

### Steps
1. Clone the repository:
git clone https://github.com/E-d-d-i-e-A/Alx_DjangoLearnLab.git cd Alx_DjangoLearnLab/django_blog
Copy code

2. Create and activate a virtual environment:
python -m venv venv
Copy code

Windows:
venv\Scripts\activate
Copy code

Mac/Linux:
source venv/bin/activate
Copy code

3. Install dependencies:
pip install -r requirements.txt
Copy code

4. Apply migrations:
python manage.py makemigrations python manage.py migrate
Copy code

5. Create a superuser (optional):
python manage.py createsuperuser
Copy code

6. Run the development server:
python manage.py runserver
Copy code

7. Open in browser:
- Home: http://127.0.0.1:8000/
- Posts: http://127.0.0.1:8000/posts/
- Admin: http://127.0.0.1:8000/admin/

---

## 📖 Usage Guide

### For Users
- Register an account and log in
- Create new blog posts with tags
- Comment on posts
- Search posts using keywords
- Filter posts by clicking on tags

### For Admin
- Access the admin panel to manage users, posts, and comments

---

## 🔌 Application Endpoints
- `/register/` – User registration  
- `/login/` – User login  
- `/logout/` – User logout  
- `/profile/` – User profile  
- `/posts/` – List all posts  
- `/post/new/` – Create post  
- `/post/<id>/` – View post  
- `/post/<id>/update/` – Update post (author only)  
- `/post/<id>/delete/` – Delete post (author only)  
- `/search/` – Search posts  
- `/tags/<slug>/` – Filter posts by tag  

---

## 🧪 Testing
- User registration and authentication
- Post creation, update, and deletion
- Comment creation and deletion
- Permission enforcement
- Search and tag filtering

---

## 🐛 Known Limitations
- No image upload functionality
- No email notifications
- Uses SQLite (development only)

---

## 🚀 Future Improvements
- Image uploads for posts
- Rich text editor
- Email notifications
- Draft posts
- User following system
- Post analytics

---

## 🎥 Presentation
A Loom video demonstrating the application in action was recorded and submitted as required by ALX.  
The video shows:
- User registration
- Post creation
- Commenting
- Search and tag filtering  
(No code walkthrough was included.)

---

## 👨‍💻 Author
**Edidiong Aquatang**  
ALX Software Engineering – Back-End Track  
GitHub: https://github.com/E-d-d-i-e-A  
Location: Lagos, Nigeria  

---

## 🙏 Acknowledgements
- **ALX Africa** for the learning structure and guidance  
- **Django Documentation** for reference and best practices  
- **django-taggit** for tag management  
- The **open-source community** for tools and resources  

---

## 📄 License
This project was created for educational purposes as part of the ALX Software Engineering Capstone Project.

**Project Status:** ✅ Completed  
**Last Updated:** December 2025