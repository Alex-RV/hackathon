//first command to install flask
pip3 install flask

//second to install WT forms
pip3 install flask-wtf

// if some errors with email install
pip3 install email_validator

// work with SQL database(command to install)
pip3 install flask-sqlalchemy

// for working with SQL use
python3
    // flask_project the name of main file in project
    from flask_project import db
        db.create_all()

// using crypt for passwords and usernames
pip3 install flask-bcrypt

//change size of image
pip3 install Pillow

//ngrok server
pip3 install flask-ngrok

//to use ngrok:
/first open this file in terminal with sudo
sudo python3 run.py
/the second is open the port
ngrok http 5000
/and copy this link from this window in terminal

//To change sql database
sudo python3
from flaskblog import db
db.create_all()
