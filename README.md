# **Django Blog Platform API**

A full-featured blogging platform built with Django and Django REST Framework, featuring user authentication, post management, commenting, tagging, and search functionality.

---

## **🚀 Features**

### **Core Functionality**
✅ **User registration and authentication**  
✅ **User profile management**  
✅ **Create, read, update, and delete blog posts**  
✅ **Comment on posts**  
✅ **Tag posts with multiple categories**  
✅ **Search posts by title, content, or tags**  
✅ **Filter posts by specific tags**

### **Security & Permissions**
✅ **Session-based authentication**  
✅ **Permission-based access control (only authors can edit/delete their content)**  
✅ **CSRF protection on all forms**  
✅ **Secure password hashing**

### **User Experience**
✅ **Responsive design for mobile and desktop**  
✅ **Pagination (5 posts per page)**  
✅ **Success/error messages for all actions**  
✅ **Clean, modern UI with smooth animations**

---

## **🛠️ Technologies Used**

- **Backend:** Django 4.2  
- **Database:** SQLite (development)  
- **Authentication:** Django built-in authentication  
- **Tagging:** django-taggit  
- **Frontend:** HTML5, CSS3, JavaScript  
- **Version Control:** Git & GitHub  

---

## **📋 Prerequisites**

- **Python 3.8 or higher**
- **pip (Python package manager)**
- **Git**

---

## **🛠️ Installation & Setup**

### **1. Clone the repository**

git clone https://github.com/E-d-d-i-e-A/Alx_DjangoLearnLab.git

cd Alx_DjangoLearnLab/django_blog

---

### **2. Create virtual environment**

python -m venv venv

**On Windows**

venv\Scripts\activate

**On Mac/Linux**

source venv/bin/activate

---

### **3. Install dependencies**

pip install -r requirements.txt 

---

### **4. Apply migrations**

python manage.py makemigrations
python manage.py migrate

---

### **5. Create superuser (admin)**

python manage.py createsuperuser 

Follow the prompts to create your admin account.

---

### **6. Run the development server**

python manage.py runserver

---

### **7. Access the application**

Homepage: http://127.0.0.1:8000/
Posts List: http://127.0.0.1:8000/posts/  
Admin Panel: http://127.0.0.1:8000/admin/

---

## **📖 Usage Guide**

### **For Users**

**Register an Account**

Click Register in the navigation

Fill in username, email, and password

You'll be automatically logged in


**Create a Post**

Click New Post after logging in

Enter title, content, and tags (comma-separated)

Click Create Post


**Comment on Posts**

Open any post

Scroll to the comments section

Write your comment and click Post Comment


**Search for Posts**

Use the search bar in the navigation

Search by title, content, or tags


**Filter by Tags**

Click any tag badge to see all posts with that tag


### **For Administrators**
Access the admin panel at:
http://127.0.0.1:8000/admin/
Admins can:
- Manage users
- Moderate posts and comments
- Manage tags
- View system data



---

## **🗂️ Project Structure**

django_blog/
├── django_blog/
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
├── blog/
│   ├── models.py
│   ├── views.py
│   ├── forms.py
│   ├── urls.py
│   ├── admin.py
│   ├── templates/
│   │   └── blog/
│   │       ├── base.html
│   │       ├── post_list.html
│   │       ├── post_detail.html
│   │       ├── post_form.html
│   │       └── …
│   └── static/
│       └── blog/
│           ├── css/
│           └── js/
├── manage.py
├── requirements.txt
└── README.md


---

## **🔌 API Endpoints**
Endpoint
Method
Description
Auth Required
/register/
GET, POST
User registration
No
/login/
GET, POST
User login
No
/logout/
POST
User logout
Yes
/profile/
GET, POST
View/edit profile
Yes
/posts/
GET
List all posts
No
/post/new/
GET, POST
Create new post
Yes
/post//
GET
View post
No
/post//update/
GET, POST
Update post
Yes (Author)
/post//delete/
GET, POST
Delete post
Yes (Author)
/post//comments/new/
POST
Add comment
Yes
/search/
GET
Search posts
No
/tags//
GET
Filter by tag
No


---

## **🧪 Testing**
- Register multiple users
- Create posts with different tags
- Attempt editing another user’s post (should fail)
- Test searching and filtering
- Add comments to posts



---

## **🐛 Known Issues**

- No image upload for posts yet
- Search is basic (not full-text)
- No email notifications



---

## **🚀 Future Enhancements**

- Rich text editor
- Image uploads
- Email notifications
- Draft posts
- Post view counter
- Social sharing



---

## **👤 Author**

**Edidiong Aquatang**

GitHub: @E-d-d-i-e-A
Email: eaquatang@gmail.com
Location: Nigeria
Program: ALX Software Engineering – Back-End Track


---

## **🙏 Acknowledgments**

- ALX Africa for guidance and structure
- Django & Django REST Framework documentation
- Open-source community



---

## **📝 License**
This project was developed as part of the ALX Software Engineering Capstone Project.



---

## **📌 Project Status**
✅ Complete



---

## **🍃 Last Updated**: December 2025



---

