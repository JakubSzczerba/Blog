# Blog
> Simple CRUD app - Blog - in Django framework

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Features](#features)
* [Setup](#setup)
* [Usage](#usage)
* [Project Status](#project-status)
* [Acknowledgements](#acknowledgements)
* [Contact](#contact)


## General Information
- It's a prototype of blog for influencers.
- Simple to install on your local computer
- everybody can do it


## Technologies Used
- Python - version 3.9.1
- Django - version 2.2.4
- db.sqlite3


## Features -> CRUD
List the ready features here:
- Creating posts
- reading posts
- updating post
- destroying posts


## Setup (examples for windows 10)
- need to install python -> https://www.python.org/downloads/windows/
- next step is create of new virtual environment in your catalog with project
```command-line
python -m venv myvenv
```
- Turn on virtual environment
```command-line
myvenv\Scripts\activate
```
- Upgrade your python version
```command-line
python -m pip install --upgrade pip
```
- Need to add requirements.txt file in your catalog with this text:
```blog/requirements.txt
Django~=2.2.4
```
- Installing Django
```command-line
pip install -r requirements.txt
```
- Create of Django project
```command-line
django-admin.exe startproject mysite .
```

## Usage
Nothing special, after turning on your local env you can add, edit and destroy post.


## Project Status
Project is: _in progress_


## To do:
- Login and Register form 
- Creating profile model

## Acknowledgements
- This project was based on this tutorial -> https://tutorial.djangogirls.org/pl/
- Many thanks to HonKit for sweet tutorial


## Contact
Created by me (with HonKit help)

