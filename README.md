# authentication-flask-demo
Web application to practice/demonstrate Authentication and Authorization using Flask.
## Major Takeaways:
Implemented user authentication, by creating a user model and storing the user information in a database.<br>
Ensured user credentialing was correct by hashing (SHA-256) the user's password from the login form and copmparing it to the hashed password stored within the database.<br>
Added authorization to the application by using the `@login_required` decorator on the profile page, so that only logged-in users could see the profile page.
## Language(s):
- Python
- HTML
- CSS
## Framework(s):
- Flask
## Modules
- Flask
- SQLAlchemy
- Various built-in Python Modules
## Installation/Setup
Run the below commands in your terminal / command line:
```
cd ...
git clone https://github.com/malcolmrichardson/authentication-flask-demo.git
cd authentication-flask-demo

python3 -m venv .venv
source .venv/bin/activate

pip3 install -r requirements.txt

export FLASK_APP=project
export FLASK_DEBUG=1

flask run
```
Application runs on http://127.0.0.1:5000 by default. Enjoy and thank you!
## Screenshots/Images: