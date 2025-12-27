# 📍 PassportPowell Travel Blog Django

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Languages](https://img.shields.io/github/languages/top/passportpowell/passportpowell-travel-blog-django)](https://github.com/passportpowell/passportpowell-travel-blog-django)

> A Django-powered travel blog and events platform with user authentication, event listings, comments, photo gallery, and an interactive quiz.

---

## 📌 Overview

This project is a full-stack **Django travel blog and community platform** that allows users to:

- Browse travel events and destinations  
- View event details and leave comments  
- Create an account, log in, and log out  
- Play an interactive travel quiz  
- Browse a photo gallery  
- Admin users manage content via the Django admin panel

The application integrates **Cloudinary** for image uploads, **PostgreSQL** for production database support, and provides a professional, responsive user experience.

---

## 📸 Screenshots

![Homepage](https://github.com/passportpowell/django-project-4/blob/main/media/Readme%20Images/am%20i%20responsive.png?raw=true)  
![Event Info](https://github.com/passportpowell/django-project-4/blob/main/media/Readme%20Images/Am%20I%20event%20info.png?raw=true)  
![Quiz Game](https://github.com/passportpowell/django-project-4/blob/main/media/Readme%20Images/Am%20I%20game.png?raw=true)  
![Gallery](https://github.com/passportpowell/django-project-4/blob/main/media/Readme%20Images/Am%20I%20gallery.png?raw=true)  
![Signup](https://github.com/passportpowell/django-project-4/blob/main/media/Readme%20Images/Am%20I%20signup%20better.png?raw=true)  
![Comments](https://github.com/passportpowell/django-project-4/blob/main/media/Readme%20Images/comment%20awaiting%20approval.png?raw=true)  
![Footer](https://github.com/passportpowell/django-project-4/blob/main/media/Readme%20Images/Am%20I%20Footer.png?raw=true)

---

## 🧠 Features

✔ Responsive home page with featured events  
✔ Django user authentication (sign up / login / logout)  
✔ Travel quiz with immediate feedback  
✔ Event details with comments (admin approval required)  
✔ Photo gallery of destinations  
✔ Cloudinary image uploads  
✔ Admin dashboard for content management

### 🛠 Django Admin Panel

![Admin Users](https://github.com/passportpowell/django-project-4/blob/main/media/Readme%20Images/Am%20I%20Django%20admin%20users.png?raw=true)  
![Admin Comments](https://github.com/passportpowell/django-project-4/blob/main/media/Readme%20Images/Am%20I%20Django%20admin%20comments.png?raw=true)  
![Admin Events](https://github.com/passportpowell/django-project-4/blob/main/media/Readme%20Images/Am%20I%20Django%20admin%20events.png?raw=true)

---

## 🚀 Future Features

* Profile pictures and personalized user profiles  
* Search functionality for events  
* Social media sign-in and sharing  
* User-generated travel content and discussion  
* Multi-language support  
* Newsletter subscriptions  
* Interactive travel maps  
* Travel video content

---

## 🐛 Bugs & Known Issues

Bugs and issues are tracked in the [Project Dashboard](https://github.com/users/passportpowell/projects/3/views/1?layout=table).

---

## 🧪 Testing

Testing included:

✔ Manual functionality testing with browsers and dev tools  
✔ Layout checks across device sizes  
✔ CSS validated via the W3C CSS Validator  
✔ Lighthouse performance and accessibility tests

![Lighthouse](https://github.com/passportpowell/django-project-4/blob/main/media/Readme%20Images/Lighthouse%20Desktop.png?raw=true)

---

## 🧱 Technology Stack

**Languages & Frameworks:**  
* Python  
* Django  
* HTML  
* CSS  
* JavaScript

**Libraries & Tools:**  
* Bootstrap  
* Font Awesome 6  
* jQuery  
* PostgreSQL  
* Gunicorn  
* Cloudinary  
* ElephantSQL  
* Pillow  
* Heroku

---

## ⚙️ Installation & Deployment

1. Clone the repository:

   ```bash
   git clone https://github.com/passportpowell/passportpowell-travel-blog-django.git
   cd passportpowell-travel-blog-django


Create and activate a virtual environment:

python3 -m venv venv
source venv/bin/activate


Install dependencies:

pip install -r requirements.txt


Set up PostgreSQL and Cloudinary, then create a .env file:

DATABASE_URL=""
SECRET_KEY=""
CLOUDINARY_URL=""


Update settings.py for database and allowed hosts.

Make migrations and migrate:

python manage.py makemigrations
python manage.py migrate


Run the server:

python manage.py runserver


For deployment (e.g., Heroku):

Create a new Heroku app

Set environment variables

Connect to GitHub or deploy via CLI

📄 Credits

Project developed with guidance from the Code Institute Full Stack Development course and support from the Slack community.

📄 License

This project is licensed under the MIT License. Feel free to use, modify, or share it.
