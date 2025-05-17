# 🧭 ALX Travel App

This is a Django-based backend API for managing travel listings, built with RESTful principles, MySQL database integration, and Swagger documentation.

## 📦 Project Features

- ✅ Django project with modular app structure
- ✅ `listings` app for handling travel-related data
- ✅ REST API powered by Django REST Framework (DRF)
- ✅ Swagger documentation via drf-yasg
- ✅ MySQL database configuration with `.env` for sensitive data
- ✅ CORS enabled for frontend integration
- ✅ Ready for Celery & RabbitMQ (future task queues)

---

## 🚀 Getting Started

### 📁 Clone the Repository

```bash
git clone https://github.com/your-username/alx_travel_app.git
cd alx_travel_app
🛠️ Setup Instructions
1. Create and activate a virtual environment
bash
Copy
Edit
python -m venv env
source env/bin/activate      # Linux/Mac
env\Scripts\activate         # Windows
2. Install dependencies
bash
Copy
Edit
pip install -r requirements.txt
3. Configure your .env file
Create a .env file in the project root and add your settings:

dotenv
Copy
Edit
DEBUG=True
SECRET_KEY=your-secret-key
DB_NAME=alx_db
DB_USER=root
DB_PASSWORD=your-password
DB_HOST=localhost
DB_PORT=3306
❗ Replace values with your actual database credentials.

4. Run Migrations
bash
Copy
Edit
python manage.py makemigrations
python manage.py migrate
5. Run the Development Server
bash
Copy
Edit
python manage.py runserver
Visit:

API Root: http://127.0.0.1:8000/api/

Swagger Docs: http://127.0.0.1:8000/swagger/

📂 Project Structure
bash
Copy
Edit
alx_travel_app/
├── alx_travel_app/         # Django project settings
│   ├── settings.py
│   ├── urls.py
│
├── listings/               # Listings app
│   ├── views.py
│   ├── urls.py
│
├── .env                    # Environment variables
├── requirements.txt
└── manage.py
🧪 Tech Stack
Python 3.12+

Django

Django REST Framework

MySQL

django-environ

django-cors-headers

drf-yasg (Swagger docs)

Celery & RabbitMQ (setup ready)

📘 API Documentation
This project uses Swagger UI provided by drf-yasg.

📄 Access it at:
http://localhost:8000/swagger/

