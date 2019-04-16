# **Preparing VS Code for Python (and Django)**

Informal document to make the best of your VS Code. 

- Install VS code
- Install Python extension

- Install dJango template extension


Open terminal (windows>New Terminal)

Put VS Code on Path "shell command: Install 'code' command in PATH". This is allow to opne the VS Code from command line. 

Go to Terminal (Comand line) > Create a folder (`mkdir`) with the name of your project. On terminal type code .

`Ritesh-MacBook-Pro:d3 RG$ mkdir myproject`

`Ritesh-MacBook-Pro:d3 RG$ code .`

**code .** Will open the VS Code 



## **Create virtual env from the VS Code**

Open the terminal and type (where env is the name of the virtual envirnoment) 

`python3 -m venv env`

`source env/bin/activate`

Press cmd+Shift+P and select 'env:venv' (venv is the name you have given to virtaul environment )

Tip: Should be able to see on botton left corner the selected interpreter/env. 

## **Download Django** 

pip install django==2.2

django-admin startproject mysite (mysite is name of your project in Django)

cd mysite

python manage.py runserver

Open http://127.0.0.1:8000

## **VS code and Django is ready** 



**Tip:** *You can select link (cmd+Shift+P) "Select linter" to choose flake8 or other linter*

------

Ritesh Gaur

