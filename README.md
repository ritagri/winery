# winery
INTRODUCTION

The goal of this project is to provide minimalistic django project for e-shop,
which just has the basic setup you can expand on.

Template is written with  PyCharm Community Edition 2022.1.3 using Django 4.1.1. (admin: rita, psw: rita)

GETTING STARTED

First clone the repository from Github and switch to the new directory:

$ git clone https://github.com/ritagri/winery.git
$ cd {{ winery}}

Activate the virtualenv for your project.

Install project dependencies:

$ pip install -r requirements/local.txt

Then simply apply the migrations:

$ python manage.py migrate

You can now run the development server:

$ python manage.py runserver
