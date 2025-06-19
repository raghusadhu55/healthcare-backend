# Healthcare Backend API

This is a Django + DRF + PostgreSQL backend for a healthcare management system.

## Features
- JWT Authentication
- Patient and Doctor CRUD APIs
- Patient-Doctor Assignment
- PostgreSQL Integration

## Setup Instructions

1. Clone the repo:
```bash
git clone https://github.com/YOUR_USERNAME/healthcare-backend.git
cd healthcare-backend
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Configure environment:
Create `.env`:
```
DB_NAME=healthcare_db
DB_USER=postgres
DB_PASSWORD=yourpassword
DB_HOST=localhost
DB_PORT=5432
```

4. Run migrations:
```bash
python manage.py makemigrations
python manage.py migrate
```

5. Start server:
```bash
python manage.py runserver
```
