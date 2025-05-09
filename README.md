# Supervillain Trading Card App
An interactive web application that allows users to create and manage a collection of supervillain trading cards. Built with Python and Flask, this app demonstrates CRUD functionality, RESTful API integration, and dynamic content rendering using Jinja templating.

## Features
Add Supervillains: Users can create new trading cards by providing details such as name, description, and interests.

Delete Supervillains: Remove existing cards from the collection seamlessly.

Dynamic Rendering: Utilizes Jinja templating to display updated content without manual page refreshes.

Responsive Design: Ensures optimal viewing experience across various devices.

## Technologies Used
Backend: Python, Flask

Frontend: HTML, CSS, JavaScript

Templating: Jinja2

Database: SQLAlchemy (SQLite)

Hosting: Replit

## Installation
### Clone the repository:

- git clone https://github.com/yourusername/supervillain-trading-card-app.git
- cd supervillain-trading-card-app
  
### Create a virtual environment:

bash
Copy
Edit
python3 -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
Install the dependencies:

- pip install -r requirements.txt
  
### Run the application:

- flask run
- The application will be accessible at http://127.0.0.1:5000/.

## Project Structure
supervillain-trading-card-app/
├── static/
│   └── styles.css
├── templates/
│   └── index.html
├── main.py
├── requirements.txt
└── README.md
main.py: The main Flask application file.

templates/index.html: The HTML template for rendering the frontend.

static/styles.css: The CSS file for styling the application.

## Screenshots
