📸 Django Photo Upload Project

This is a simple Photo Upload project built using Django, where users can upload and store multiple images. The uploaded images are displayed on the home page, allowing users to keep as many photos as they want.


🚀 Features
Users can upload multiple images.
Uploaded images are stored and displayed dynamically.
Uses Django forms to handle image uploads.

🛠️ Technologies Used
Django
HTML, CSS
SQLite (Default Django Database)


📂 Project Structure
The project directory is named imageuploader-main and contains the necessary files for the Django application.

Django-Project/ │── imageuploader-main/ # Main project folder │ ├── myapp/ # Django app │ │ ├── templates/ # HTML templates │ │ ├── forms.py # Form handling │ │ ├── models.py # Database models │ │ ├── views.py # Business logic │ ├── manage.py # Django project manager │ ├── db.sqlite3 # SQLite database (default) │ ├── requirements.txt # Dependencies file │ ├── README.md # Project documentation

🖥️ Setup Instructions
Clone the repository
git clone https://github.com/Premnarayan-Sadh/Django-Project.git
cd Django-Project/imageuploader-main
Create and activate a virtual environment (optional but recommended)

python -m venv venv source venv/bin/activate # On Windows use: venv\Scripts\activate Install dependencies

pip install -r requirements.txt Apply migrations

python manage.py migrate Run the development server

python manage.py runserver

Open your browser and visit: http://127.0.0.1:8000/

🤝 Contributing Feel free to fork this repository and contribute!
