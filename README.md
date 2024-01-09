![Python 3.11](https://img.shields.io/badge/python-3.11-blue.svg)
![Django](https://img.shields.io/badge/django-5.0.1-092E20.svg)
![SQLite](https://img.shields.io/badge/sqlite-3.x-07405E.svg)
![Web Frameworks](https://img.shields.io/badge/web%20frameworks-Django-blue.svg)


# Django Job Application Portal

## Overview
This Django application serves as a job application portal. It allows users to submit their application details through a form, which are then stored in a database. A confirmation email is sent to the user upon successful submission. The application features two primary views: the application form (`index`) and an informational page (`about`).

## Features
- **Form Submission**: Users can submit details like first name, last name, email, date, and occupation.
- **Email Confirmation**: Sends a confirmation email upon successful form submission.
- **Success Notification**: Displays a success message on the website after form submission.
- **Responsive UI**: Includes 'index' for the application form and 'about' for additional information.

## Installation
Ensure Python and Django are installed on your system. Follow these steps:

1. **Clone the Repository**:
   ```
   git clone [repository-link]
   ```
2. **Navigate to the Application Directory**:
   ```
   cd [app-directory]
   ```
3. **Install Required Packages**:
   ```
   pip install -r requirements.txt
   ```

## Database Setup
Before running the application, set up the database:

1. **Configure Database Settings**:
   Update `settings.py` with your database configuration.

2. **Run Migrations**:
   Make migrations for your models:
   ```
   python manage.py makemigrations
   ```
   Apply the migrations to the database:
   ```
   python manage.py migrate
   ```

## Running the Server
Start the Django server:
```
python manage.py runserver
```
Access the application at `http://localhost:8000/`. Use the form on the main page to submit applications. Visit `http://localhost:8000/about` for additional information.

## Configuration
- Configure email backend settings in `settings.py` for email functionality.
- Customize form fields and validations in `forms.py`.

## Contributing
Contributions to this project are welcome. Please follow these steps:

1. Fork the repository.
2. Create a feature branch (`git checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -am 'Add some YourFeature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a pull request.

## License
This project is licensed under the MIT License 

**Note**: Replace `[repository-link]` and `[app-directory]` with actual values. Ensure to provide correct database configurations in `settings.py`. This README assumes a standard Django project structure and default settings.

## Final Look
![frontend.png](images%2Ffrontend.png)

![admin.png](images%2Fadmin.png)

