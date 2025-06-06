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

How to Run the Project Locally:
-------------------------------

1. Create a virtual environment:

   python -m venv venv
   source venv/bin/activate      # On Windows: venv\Scripts\activate

2. Install dependencies:

   pip install -r requirements.txt

3. Apply database migrations:

   python manage.py makemigrations
   python manage.py migrate

4. Start the development server:

   python manage.py runserver

5. Open your browser and go to:

   http://127.0.0.1:8000/ to view the app.
