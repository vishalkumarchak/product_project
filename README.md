# Django Product Management System

## Project Overview

This is a Django-based Product Management System with a Custom Admin Panel. The project allows administrators to manage products without using Django's default admin interface.

## Features

* Custom Admin Login
* Dashboard
* Product Create
* Product Read
* Product Update
* Product Delete
* Product Image Upload
* Authentication System
* Responsive User Interface
* Database Integration using Django ORM

## Technology Stack

* Python
* Django
* HTML
* CSS
* SQLite
* Bootstrap (Optional)

## Project Structure

```
product_project/
│
├── product_project/
│   ├── settings.py
│   ├── urls.py
│
├── product_app/
│   ├── migrations/
│   ├── models.py
│   ├── views.py
│   ├── forms.py
│   ├── urls.py
│
├── templates/
│   ├── login.html
│   ├── dashboard.html
│   ├── add_product.html
│   └── product_list.html
│
├── media/
│
├── manage.py
└── README.md
```

## Product Model

Fields used in Product Model:

* Product Name
* Price
* Description
* Product Image

## Installation

### Clone Repository

```bash
git clone <repository-url>
```

### Create Virtual Environment

```bash
python -m venv venv
```

### Activate Virtual Environment

Windows:

```bash
venv\Scripts\activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Migrations

```bash
python manage.py makemigrations
python manage.py migrate
```

### Create Superuser

```bash
python manage.py createsuperuser
```

### Start Server

```bash
python manage.py runserver
```

## Application URLs

| URL                   | Description    |
| --------------------- | -------------- |
| /                     | Login Page     |
| /dashboard/           | Dashboard      |
| /add-product/         | Add Product    |
| /products/            | Product List   |
| /update-product/<id>/ | Update Product |
| /delete-product/<id>/ | Delete Product |

## CRUD Operations

### Create

Admin can add new products with image upload.

### Read

Admin can view all available products.

### Update

Admin can modify existing product details.

### Delete

Admin can remove products from the database.

## Authentication

User authentication is implemented using Django's built-in authentication system.

## Future Enhancements

* Product Categories
* Search Functionality
* Pagination
* User Roles & Permissions
* REST API Integration
* AJAX Operations
* Soft Delete Feature

## Learning Outcomes

Through this project, the following Django concepts were implemented:

* Django ORM
* Models
* Forms
* Views
* URL Routing
* Authentication
* Template Rendering
* Media File Handling
* CRUD Operations
* Custom Admin Panel

## Author

Vishal Chak

Python Django Developer
