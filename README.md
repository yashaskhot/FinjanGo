# FinTrack Djan

Finance tracker with expenses visualisation and crud Operations.
## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)

## Project Overview

A Finance tracking application where you can add,edit and delete expenses and get an overview using various charts.

## Features

- Add, Edit, Delete Expenses & Incomes
- Visualize and Understand your expenditure better
- Secure email verification and Login

## Requirements

- Python3
- Django 
- MySql DB 
- SMTP Mail

## Installation

### Setting up a Virtual Environment

It's recommended to use `pipenv` to create and manage a virtual environment for your project. Follow these steps to set up a virtual environment:

1. Install `pipenv` if you haven't already:

   pip install pipenv

2. Clone the repository:

   ```bash
   git clone https://github.com/yashaskhot/FJ-BE-R2--Yashas-Khot--Don-Bosco-Institute-of-Technology-Mumbai.git
   ```

3. Navigate to the project directory:

   ```bash
   cd expenseswebsite/
   ```

4. Create a virtual environment and install project dependencies:

   ```bash
   pipenv install --dev
   ```

5. Activate the virtual environment:

   ```bash
   pipenv shell
   ```

### Installing Project Dependencies

After setting up the virtual environment, you can install project dependencies:

```
pipenv install
```

### Running Migrations

Perform initial database migrations:

python manage.py migrate


## Usage

Explain how to use your Django project once it's installed and set up. Provide examples or instructions for common tasks and workflows.

## Run the development server
python manage.py runserver


## Set environment variables
```
DATABASES = {
    
    'default': {
        'ENGINE': 'django.db.backends.mysql', 
        'NAME': 'Your DB Name',
        'USER': 'Your MySQL username',
        'PASSWORD': 'Your MySQL Password',
        'HOST': 'localhost',   # Or an IP Address that your DB is hosted on
        'PORT': '3306', 
    }
}

EMAIL_HOST = 'smtp.gmail.com'
EMAIL_HOST_USER = 'your valid mail'
EMAIL_USE_TLS = True
DEFAULT_FROM_EMAIL = 'same as host user'
EMAIL_PORT = 587
EMAIL_HOST_PASSWORD = '' #create an app password for your mail
EMAIL_BACKEND = 'django.core.mail.backends.smtp.EmailBackend'

```



