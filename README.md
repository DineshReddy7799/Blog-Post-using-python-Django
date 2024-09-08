Django Blog - Beginner Level
This is a basic blog application built using Django. It allows users to create, read, and delete blog posts. Authentication is implemented to restrict certain actions to logged-in users only. The project is designed for beginners to learn the fundamentals of Django.

Features
User authentication (login, logout, registration).
Create, read, and delete blog posts (only for authenticated users).
View a list of all posts.
Simple user interface.
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/django-blog-beginner.git
Navigate to the project directory:

bash
Copy code
cd django-blog-beginner
Create a virtual environment:

bash
Copy code
python -m venv venv
Activate the virtual environment:

On Windows:

bash
Copy code
venv\Scripts\activate
On macOS/Linux:

bash
Copy code
source venv/bin/activate
Install the dependencies:

bash
Copy code
pip install -r requirements.txt
Apply migrations:

bash
Copy code
python manage.py migrate
Create a superuser:

bash
Copy code
python manage.py createsuperuser
Run the server:

bash
Copy code
python manage.py runserver
Open the app in your browser:

arduino
Copy code
http://127.0.0.1:8000/
Usage
Authentication:
Register a new account.
Log in to access features like creating and deleting posts.
Log out when done.
Homepage: Lists all blog posts.
Create Post: Add a new post (only for logged-in users).
Delete Post: Remove a post (only for logged-in users).
