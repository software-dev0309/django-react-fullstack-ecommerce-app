# 🛒 E-Commerce Platform

A full-stack e-commerce web application built with **Django**, **Django REST Framework**, **React**, and **PostgreSQL**, designed for selling products such as hats, ponchos, backpacks, hammocks, and accessories.

## 🚀 Features

### 🌐 Frontend (React)
- Responsive UI with React + Tailwind CSS
- Product listing and filtering
- Product detail pages with high-resolution images
- Shopping cart with quantity management
- Stripe Checkout integration
- User login, registration, and profile dashboard
- Order summary & status tracking

### ⚙️ Backend (Django + DRF)
- RESTful API with Django REST Framework
- Product, category, and inventory management
- Order and payment tracking
- Secure user authentication (JWT)
- Admin panel for product & order control
- Image handling with AWS S3 (or local media)

### 💳 Payments
- Integrated with **Stripe** for secure payments
- Supports Colombian Pesos (COP) currency

### 🗄️ Database
- PostgreSQL for robust relational data management

## 🏗️ Tech Stack

- **Backend:** Django, Django REST Framework
- **Frontend:** React, Axios, Tailwind CSS
- **Database:** PostgreSQL
- **Authentication:** JWT
- **Payments:** Stripe API
- **Media Storage:** AWS S3 (or Django media folder)
- **Deployment:** Docker / Docker Compose / Gunicorn / Nginx

## 🛠️ Installation (Development)

1. Clone the Repository  
```bash
git clone https://github.com/software-dev0309/django-react-fullstack-ecommerce-app.git
cd django-react-fullstack-ecommerce-app

2. Backend Setup (Django)
```bash
Copy
Edit
cd backend
python -m venv env
source env/bin/activate
pip install -r requirements.txt
cp .env.example .env
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver

3.Frontend Setup (React)
```bash
cd frontend
npm install
npm start
