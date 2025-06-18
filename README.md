# 💬 Echo Room – A Real-Time Communication Platform for Modern Teams
![452561225-9e61efba-0131-4694-a305-5bed799ed7a2](https://github.com/user-attachments/assets/26a5d678-98e8-4ded-910e-4d32d6d4352d)

This project is a simple **web application** built using the Django framework. It demonstrates core full-stack development concepts like:

- User authentication
- Dynamic content rendering
- Database integration

---

## ✨ Features

- 🔐 User registration, login, and logout  
- 💬 Topic-based chat rooms with messages  
- ✍️ Create, update, and delete rooms/messages  
- 👤 User profiles and activity tracking  
- 🎨 Frontend: HTML, CSS, JavaScript  
- 🧠 Backend: Django & Django ORM  

---

## 🛠 How to Run the Project Locally

Follow these steps to set up and run the Django project on your local machine:

### 1️⃣ Clone the repository
Install Git from the Official Website: https://git-scm.com/downloads
```bash
git clone https://github.com/rhemanth832/Discord_Clone.git
cd Echo_Room
```

### 2️⃣ Create and activate a virtual environment
```bash
python -m venv venv
# On Windows:
venv\Scripts\activate
```

```bash
# On macOS/Linux:
source venv/bin/activate
```

### 3️⃣ Install Django and dependencies
```bash
pip install django
pip install -r requirements.txt
pip install django-heroku
pip install djangorestframework
pip install Pillow
```

### 4️⃣ Apply database migrations
```bash
python manage.py migrate
```

### 5️⃣ Start the development server
```bash
python manage.py runserver
```

### 6️⃣ Open in your browser
Visit: [http://127.0.0.1:8000/](http://127.0.0.1:8000/) to view the app.

---

## 📁 Project Structure

```
Echo_Room/
├── app/
│   ├── templates/
│   ├── static/
│   └── views.py
├── manage.py
├── db.sqlite3
└── requirements.txt
```
