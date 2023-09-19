# Society-Management-Application
🏘️ A web app for society management, facilitating house sales/rentals, featuring a news carousel, complaint submission, and direct contact with the manager. New users receive a Gmail OTP for registration verification.

## 🚀 Features
- User Registration with Gmail OTP verifications
- Latest news from their own society management admins
- Admin exclusive features like adding news to be shown to everyone living in their society
- Recent Visitors list
- Application forms to buy and rent flats
- Complaint feature and Contact support

## 📚 What I've learned
- Focused a lot on learning Django framework
- Learnt the containerization using Docker
- Sending emails using SMTP servers
- Celery workers
- And much more...


## ⚡ Main Technologies
<code>Python</code> <code>Django</code> <code>HTML</code> <code>CSS</code> <code>JavaScript</code> <code>Postgresql</code> <code>Jinja2</code> <code>Docker</code> <code>Redis</code> <code>Celery</code>

## ⚙️ Installation
```bash
# Clone the repository to your local machine.
git clone https://github.com/VishnuKumarSS/Society-Management-Application.git
```
**Create & Activate the Virtual Environment:**
```bash
# Create the virtual environment
$ python -m venv venv

# Activate the virtual environment in Windows (In git bash)
$ source venv/Scripts/activate
# Activate the virtual environment in Linux/Mac
$ source venv/bin/activate
```
**Install the required python packages:**
```bash
$ pip install -r requirements.txt
```
## Run the application:
```bash
# Create and Apply migrations
$ python manage.py makemigrations
$ python manage.py migrate

# Create superuser to help managing for the first time
$ python manage.py createsuperuser

# To start the Django server
$ python manage.py runserver
```
**View the app:**
> Open http://127.0.0.1:8000/ (or the address shown in your console) in your web browser to view the app.