# Flask-WTF Tutorial

![Python](https://img.shields.io/badge/Python-v^3.8-blue.svg?logo=python&longCache=true&logoColor=white&colorB=5e81ac&style=flat-square&colorA=4c566a)
![Flask](https://img.shields.io/badge/Flask-v1.1.1-blue.svg?longCache=true&logo=flask&style=flat-square&logoColor=white&colorB=5e81ac&colorA=4c566a)
![Flask-WTF](https://img.shields.io/badge/Flask--WTF-v0.14.2-blue.svg?longCache=true&logo=flask&style=flat-square&logoColor=white&colorB=5e81ac&colorA=4c566a)
![GitHub Last Commit](https://img.shields.io/github/last-commit/google/skia.svg?style=flat-square&colorA=4c566a&colorB=a3be8c&logo=GitHub)
[![GitHub Issues](https://img.shields.io/github/issues/hackersandslackers/flask-wtform-tutorial.svg?style=flat-square&colorA=4c566a&logo=GitHub&colorB=ebcb8b)](https://github.com/hackersandslackers/flask-wtform-tutorial/issues)
[![GitHub Stars](https://img.shields.io/github/stars/hackersandslackers/flask-wtform-tutorial.svg?style=flat-square&colorA=4c566a&logo=GitHub&colorB=ebcb8b)](https://github.com/hackersandslackers/flask-wtform-tutorial/stargazers)
[![GitHub Forks](https://img.shields.io/github/forks/hackersandslackers/flask-wtform-tutorial.svg?style=flat-square&colorA=4c566a&logo=GitHub&colorB=ebcb8b)](https://github.com/hackersandslackers/flask-wtform-tutorial/network)

![Flask-WTF Tutorial](https://github.com/hackersandslackers/flask-wtform-tutorial/blob/master/.github/flask-wtforms-tutorial@2x.jpg?raw=true)

Source code for the accompanying tutorial found here: https://hackersandslackers.com/flask-wtforms-forms/


# Getting Started

Get set up locally in two steps:

### Environment Variables

Replace the values in **.env.example** with your values and rename this file to **.env**:

* `FLASK_APP`: Entry point of your application (should be `wsgi.py`).
* `FLASK_ENV`: The environment to run your app in (either `development` or `production`).
* `SECRET_KEY`: Randomly generated string of characters used to encrypt your app's data.

*Remember never to commit secrets saved in .env files to Github.*


### TODO

**Config.py** 

1- set up secret key variable 
2- load .env file

**forms.py**
1- create a signup form to include [email - password - confirm password - title - website - birthday - recapthcha - submit]
2- use appropriate field types and validations for the previous items 

**routes.py**

1- complete the sign up route

Tip: u can use WTFORMS way of checking whether the request GET or POST   
-----

**Hackers and Slackers** tutorials are free of charge. If you found this tutorial helpful, a [small donation](https://www.buymeacoffee.com/hackersslackers) would be greatly appreciated to keep us in business. All proceeds go towards coffee, and all coffee goes towards more content.
