![Flask](https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white)

## Introduction to Flask 

Flask is a web framework that has tools that allow us to create web applications

### Basic application structure

To have a basic flask application you have to have done the following:

- Set up your working environment
- Created a virtual environment from where you will work on created a flask application.
- Activated the virtual environment 
When the virtual environment is active the terminal responds with the name of the virtual environment before your device/ computer's name.
- Installed flask inside your virtual environment 

*Find help [here to set](https://github.com/Reuben-Kipkemboi/Flask-Cheatsheet) up your environment before staerting working on the application*

**BAsic flask app**

Inside the Flask application create a new file named `friday.py`

Add the following code in your friday.py file

```py
from flask import Flask
app = Flask(__name__)
```

from the flask module we import the Flask class. We then create an instance of that class called app, by passing in the `__name__` variable.

Flask uses the `__name__` variable to determine the root path for the application




