# HospitalManagement_Django

This project was developed by Shreyas and Uday.

## Getting Started

Follow these instructions to set up and run the application on your local machine.

### Prerequisites

Ensure you have the following installed:
- Python 3.x
- pip

### Installation

1. **Clone the repository**
   ```sh
   git clone https://github.com/ShreyasGowda28/HospitalManagement_Django.git
   cd HospitalManagement_Django
   ```

2. **Install the Requirements**
   ```sh
   pip install xhtml2pdf
   pip install Django==3.0.5
   pip install django-widget-tweaks==1.4.8
   pip install sqlparse==0.3.1

   ```

3. **Make Database Migrations**
   ```sh
   python manage.py makemigrations
   python manage.py migrate
   ```

4. **Run the Application**
   ```sh
   python manage.py runserver
   ```

### Creating an Admin Account

To access the admin interface, create a superuser account:

```sh
python manage.py createsuperuser
```

Follow the prompts to set up your admin username, email, and password.

## Usage

1. After starting the server, open your web browser and go to `http://127.0.0.1:8000/` to access the application.
2. To access the admin panel, go to `http://127.0.0.1:8000/admin/` and log in with the superuser account you created.

