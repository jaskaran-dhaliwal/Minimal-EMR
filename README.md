﻿This project builds on the work of the open-source Django EHR

## Introduction

DjangoEHR is an Electronic Health Records (EHR) system developed using the Django web framework. This project aims to provide healthcare professionals with a robust and secure platform for managing patient records, appointments, and medical information.

## Features

- User Authentication: Secure user authentication and role-based access control for healthcare providers and staff.
- Patient Management: Easily add, update, and view patient records, including personal information, medical history, and insurance details.
- Appointment Scheduling: Schedule patient appointments with a user-friendly calendar interface, complete with reminders and notifications.
- Medical Records: Store and manage electronic medical records, including diagnoses, treatments, and lab results.
- Billing and Insurance: Track patient billing information, insurance claims, and payment history.
- Reporting and Analytics: Generate reports and insights for better decision-making and patient care.
- Customization: Easily extend and customize the system to suit the specific needs of your healthcare facility.

## Installation

To get started with DjangoEHR, follow these installation steps:

1. Clone the repository to your local machine:

    ```bash
    git clone https://github.com/MohsinRazaKhanSipra/djangoehr.git
    ```

2. Create a virtual environment and activate it:

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. Install project dependencies:

    ```bash
    pip install -r requirements.txt
    ```

4. Configure your database settings in the `settings.py` file.

5. Apply database migrations:

    ```bash
    python manage.py migrate
    ```

6. Create a superuser account:

    ```bash
    python manage.py createsuperuser
    ```

7. Start the development server:

    ```bash
    python manage.py runserver
    ```

8. Access the admin interface at [http://localhost:8000/admin/](http://localhost:8000/admin/) and log in with your superuser credentials to start using DjangoEHR.

