# Hospital Management System

## Application Domain
This is a Django-based web application that serves as a Hospital Management System.

## Setup Instructions

### 1. Clone the repository 
```powershell
git clone https://github.com/rene3phillips/django_assignment_1
cd django_assignment_1
```

### 2. Create and activate a virtual environment
```powershell
python -m venv venv
.\venv\Scripts\activate
```

### 3. Install required dependencies
```powershell
pip install -r requirements.txt
```

### 4. Create a .env file 
Create a `.env` file based on `env.example` and fill in actual database credentials. 

### 5. Run Migrations
```powershell
python manage.py migrate
```

### 6. Create a superuser
```powershell
python manage.py createsuperuser
```
Follow the prompts to create a user account for the Django admin site.

### 7. Run the development server
```powershell
python manage.py runserver
```