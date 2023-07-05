Flask Donation App
Welcome to Flask Donation App! This is a full-stack application built using Flask, a popular micro-framework in Python, alongside HTML, CSS and JavaScript. This application provides a simple yet elegant way to handle donations for a cause. It features different interfaces for a donation center, allowing users to donate in various ways.

Project Structure
This Flask project follows a typical structure for a small Flask application:
/Flask-Donation-App
  /static
    /css
      - style.css
  /templates
    - dashboard.html
    - index.html
    - login.html
    - register.html
  - app.py
  - README.md
The static folder holds the static files like CSS, while the templates folder contains the HTML templates. The main logic of the application resides in the app.py file.
Features
The application currently supports the following features:

User registration and login system.
A user dashboard to simulate the donation process.
SQLite database integration for data persistence using SQLAlchemy.
Flask-Migrate for handling database migrations.

Setup Instructions
To get this project running in your local development environment, follow these steps:
Clone this repository to your local machine.
Navigate to the project directory.
(Optional, but recommended) Create a virtual environment.
Install the required dependencies using pip: pip install -r requirements.txt.
Set the FLASK_APP environment variable to app.py: export FLASK_APP=app.py (on Unix) or set FLASK_APP=app.py (on Windows).
Run the application: flask run.
Open your browser and navigate to http://localhost:5000.

Future Improvements
This project is a starting point and can be significantly expanded and improved. Future updates may include:

Form validation and better error handling.
Adding tests.
More interactive frontend with a framework like Vue.js or React.
Implementing real payment gateways like Stripe or PayPal.

Contributions
Contributions to this project are welcome! If you find a bug or think of a feature that would be a great addition to the project, please open an issue or submit a pull request.
