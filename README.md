Project Title: Personal Portfolio Website using Python (Flask)

Objective:
The goal of this project is to create a personal portfolio website to showcase skills, projects, and contact information. It also includes a contact form for visitors to send messages.

Technology Stack:

Backend: Python (Flask framework)

Frontend: HTML5, CSS3

Others: Jinja2 templating (for dynamic HTML rendering), Static file handling in Flask

Working Principle:

Flask Routing:

The app uses Flask routes to handle different pages:

/ → Home Page (introduction, about, projects)

/contact → Contact Page (form for messages)

Templates:

HTML files located in the templates/ folder display the site content.

Jinja2 template syntax ({{ }}, {% %}) is used to pass data from Python to HTML.

Static Files:

CSS, images, and other static content are stored in the static/ folder and served by Flask.

Contact Form:

Users can submit a name, email, and message.

In this basic version, submitted data is printed to the terminal (can be extended to save to a database or email).

Outcome:

A fully functional, mini personal portfolio website that runs locally and can be deployed online.

It demonstrates web development concepts like routing, templates, and form handling in Flask.
