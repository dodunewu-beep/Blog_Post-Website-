📝 Flask Blog Website
Overview

A web-based blog platform built with Python and Flask that allows users to register, log in securely, and view blog posts. Administrators can create, edit, and delete posts through the application.

The project demonstrates the development of a database-driven web application with user authentication and content management functionality.

Key Features
👤 User registration and login
🔐 Password hashing for secure authentication
📝 Create and manage blog posts
✏️ Edit existing posts
🗑️ Delete posts
🖼️ Support for post images
📖 Individual blog post pages
📱 Bootstrap-based interface
🗄️ SQLite database for storing users and posts
📄 About and Contact pages
How It Works
Users register with their name, email, and password.
Passwords are securely hashed before being stored.
Registered users can log in and access the blog.
Blog posts are stored in the SQLite database.
Posts can be viewed individually or as a collection.
Administrative functionality allows posts to be created, edited, and deleted.
🛠️ Technology Stack
Python
Flask – Web application framework
SQLAlchemy – Database management
SQLite – Database
Flask-Login – User authentication
Flask-WTF – Form validation
Bootstrap 5 – User interface
CKEditor – Rich-text content editing
Werkzeug – Password hashing
📁 Project Structure
blog-project/
├── main.py
├── forms.py
├── requirements.txt
├── templates/
│   ├── index.html
│   ├── post.html
│   ├── register.html
│   ├── login.html
│   ├── make-post.html
│   ├── about.html
│   └── contact.html
├── static/
│   └── ...
└── posts.db

🚀 Setup

Install the required packages:

pip install -r requirements.txt


Run the application:

python main.py


The application runs locally on:

http://127.0.0.1:5002

🔐 Security

The application uses password hashing through Werkzeug rather than storing passwords as plain text.

For production use, the Flask SECRET_KEY and other sensitive configuration values should be stored securely using environment variables rather than directly in the source code.

🔮 Future Development
🔒 Improved role-based access control
💬 User comments
❤️ Post likes/reactions
🔎 Search functionality
📑 Pagination
👤 User profile pages
☁️ Production database and hosting
🛡️ Enhanced security and error handling
🎯 Project Outcome

This project demonstrates the ability to build a full-stack, database-driven web application with authentication, form validation, CRUD functionality, and a responsive user interface.

It provides a foundation that can be extended into a production-ready blogging or content-management platform.
