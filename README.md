# Healthcare Backend API

This is a Django + DRF + PostgreSQL backend for a healthcare management system.

# Objective

To develop a secure and scalable RESTful API backend for a healthcare system, enabling the management of patients, doctors, and their relationships using Django, DRF, PostgreSQL, and JWT.

## Features
- JWT Authentication
- Patient and Doctor CRUD APIs
- Patient-Doctor Assignment
- PostgreSQL Integration

# Key Features Implemented
Authentication System
User Registration (/api/auth/register/)

JWT Login (/api/auth/login/)

Secure token-based access to all other APIs.

# Patient Management
Authenticated users can:

Create patients

View only their own patients

Update or delete patient records
# Doctor Management
Any authenticated user can:

Add, view, edit, delete doctors

View full doctor list (not user-specific)

# Patient-Doctor Mapping
Patients can be assigned to multiple doctors

Endpoints to:

Map doctor to patient

List all mappings

Get mappings for a specific patient

Remove a mapping
