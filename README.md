# Django Contact Book Project

This is a simple contact book web application built with Django.

## Setup

Follow these steps to set up the project:

1. **Clone the repository:**
   ```bash
   git clone <repository-url>
   ```
2. **Navigate to the project directory:**
   ```bash
   cd django-contact-book
   ```
3. **Create a virtual environment:**
   ```bash
   python -m venv env
   ```
4. **Activate the virtual environment:**
   ```bash
   .\env\Scripts\activate
   ```
5. **Install the project dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
6. **Apply database migrations:**
   ```bash
   python manage.py migrate
   ```
7. **Create a superuser to access the admin interface:**
   ```bash
   python manage.py createsuperuser
   ```
8. **Start the development server:**
   ```bash
   python manage.py runserver
   ```
9. **Open your web browser and navigate to http://127.0.0.1:8000 to view the application.**

## Usage
Use the application to manage your contacts.
Access the admin interface at http://127.0.0.1:8000/admin to manage contacts and users (requires superuser credentials).
Contributing
Contributions are welcome! Please follow these steps to contribute:

## Fork the repository.
Create a new branch (git checkout -b feature/my-feature).
Make your changes.
Commit your changes (git commit -am 'Add new feature').
Push to the branch (git push origin feature/my-feature).
Create a new pull request.
