# E-commerce Website Project

This project is a Django-based e-commerce website that utilizes Oracle 19c as the database backend. Follow the instructions below to set up the project on your local machine.

## Prerequisites

- Oracle Database 19c
- Python 3.x
- Django

## Setup Instructions

### 1. Install Oracle Database 19c

Before running the project, ensure you have Oracle Database 19c installed on your machine. Follow the official Oracle installation guide for your specific operating system.

### 2. Clone the Project

Clone the repository to your local machine using the following command:
git clone https://github.com/talib-raath/ecommerce-Website


### 3. Install Python

The project is developed using Django, which requires Python. Download and install Python 3.x from the [official Python website](https://www.python.org/).

### 4. Install Django

With Python installed, use pip to install Django:

pip install django


### 5. Configure the Database

Navigate to the project's `settings.py` file and modify the `DATABASES` dictionary with your Oracle database connection details (username, password, etc.).

### 6. Apply Database Schema

Run the SQL code provided in `extras>inventory.sql` to create the necessary database schema. This step requires access to your Oracle 19c database.

### 7. Run Migrations

Django uses migrations to manage database schema changes. Apply migrations using the following command:

python manage.py migrate


### 8. Create a Django Superuser

Create a superuser for the Django admin panel:


Follow the prompts to set up the superuser account.

### 9. Run the Server

Start the Django development server:

python manage.py runserver


Navigate to `http://127.0.0.1:8000/` in your web browser to view the project.

## Project Screenshots
![Screenshot of Feature X](/screenshots/ss2.jpeg "Feature X Preview")
![Screenshot of Feature X](/screenshots/ss6.jpeg "Feature X Preview")
![Screenshot of Feature X](/screenshots/ss1.jpeg "Feature X Preview")
![Screenshot of Feature X](/screenshots/ss3.jpeg "Feature X Preview")
![Screenshot of Feature X](/screenshots/ss4.jpeg "Feature X Preview")
![Screenshot of Feature X](/screenshots/ss5.jpeg "Feature X Preview")

## Contributions

Contributions to the project are welcome. Please fork the repository and submit a pull request with your changes.


## License

This project is licensed under the MIT License - see the LICENSE.md file for details.
