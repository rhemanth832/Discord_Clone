Discord Clone – Made with Django
===============================

This project is a simple Discord-inspired web application built using the Django framework. It demonstrates core full-stack development concepts like user authentication, dynamic content, and database integration.

Features:
---------
- User registration, login, and logout
- Topic-based chat rooms with messages
- Create, update, and delete rooms/messages
- User profiles and activity tracking
- Frontend: HTML, CSS, JavaScript
- Backend: Django and Django ORM

How to Run the Project Locally
-------------------------------

Follow these steps to set up and run the Django project on your local machine:

1. Create and activate a virtual environment:

   python -m venv venv
   On Windows: venv\Scripts\activate
   On macOS/Linux: source venv/bin/activate

2. Install Django:

   pip install django

3. Install required dependencies:

   pip install -r requirements.txt
   pip install django-heroku
   pip install djangorestframework
   pip install Pillow

4. Apply database migrations:

   python manage.py migrate

5. Start the development server:

   python manage.py runserver

6. Open your browser and go to:

   http://127.0.0.1:8000/ to view the app.
