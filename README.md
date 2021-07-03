#This is the project for making webapp without any framwork in python 

#Here we using gunicorn webserver for hosting purpose

#inthis tutorial i done on android mobile so virtualenv activation method will be different.if compare to windows ...


#To start project
1.make directory for your project.
2.go to your project folder inside through ide or cmd prompt or termux or terminal.


#To make virtualenv:
python -m venv myvenv

#To activate virtualenvirenment:
source myenv/bin/activate

after activate venv you will see 
(myenv)$ like this

#To install gunicorin:
pip install gunicorn

#To work with file of your project:
1.make html files which are u want to see in your webpages exam(index.html,contact html,404.html)

2.make server.py file for make functionating the webapp.


#To start gunicorn web app
gunicorn server:app --reload