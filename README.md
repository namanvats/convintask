# convintask
Convin Task

# Installation process 

## Install the system dependencies
* **git** 
* **pip**

## Get the code
* Clone the repository

## Install the project dependencies

`pip install -r requirements.txt`

## Run the command to generate the database
`python manage.py migrate`

## Generate super user
`python manage.py createsuperuser`

## Run the server
`python manage.py runserver` the application will be running on port 8000 ** http://127.0.0.1:8000/**
* `Admin page :  http://127.0.0.1:8000/admin`
* `Tasks :  http://127.0.0.1:8000/apis/v1/`
* `Task Tracker :  http://127.0.0.1:8000/apis/v2/`

## End Points

### Tasks
* `GET /apis/v1/{pk}`
* `POST /apis/v1/{pk}`

### TaskTrackers
* `GET /apis/v2/{pk}`
* `POST /apis/v2/{pk}`
