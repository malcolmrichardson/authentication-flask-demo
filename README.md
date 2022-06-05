# authentication-flask-demo
Web application to practice/demonstrate Authentication and Authorization using Flask.
## Major Takeaways:
1. Implemented user authentication, by creating a user model and storing the user information in a database.
2. Ensured user credentialing was correct by hashing (SHA-256) the user's password from the login form and copmparing it to the hashed password stored within the database.
3. Added authorization to the application by using the `@login_required` decorator on the profile page, so that only logged-in users could see the profile page.
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

<img width="1552" alt="Screen Shot 2022-06-04 at 10 53 32 PM" src="https://user-images.githubusercontent.com/70815205/172033125-f3c0f041-52cb-4490-b833-6e4e38a8c3d8.png">
<img width="1552" alt="Screen Shot 2022-06-04 at 10 53 45 PM" src="https://user-images.githubusercontent.com/70815205/172033129-df2ba51b-f8be-4915-b157-02d665dbd24a.png">
<img width="1552" alt="Screen Shot 2022-06-04 at 10 53 56 PM" src="https://user-images.githubusercontent.com/70815205/172033132-6576ac9e-c8d8-4671-8dde-4bfd30d78209.png">
<img width="1552" alt="Screen Shot 2022-06-04 at 10 54 24 PM" src="https://user-images.githubusercontent.com/70815205/172033140-52d83482-81ef-4838-ba38-6405bd469861.png">
<img width="1552" alt="Screen Shot 2022-06-04 at 10 54 33 PM" src="https://user-images.githubusercontent.com/70815205/172033144-c45da707-f525-4819-a69f-2b62d3b4d95f.png">
