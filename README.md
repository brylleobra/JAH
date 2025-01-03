JAH: Job Application Helper

## Project Building ##

All project files initialized

Backend: FastAPI (to be checked if this should be changed to Django)
Frontend: React.js
DB: Postgre

-------------------------

After cloning repository make sure docker desktop is enabled on your end

to run the application:
$ docker-compose build
$ docker-compose up


For any changes on the Dockerfile run:

$ docker-compose down --rmi all
$ docker-compose build
$ docker-compose up

To access app on local:
Frontend: http://localhost:3000
Backend: http://localhost:8000 (base URL)
Postgre: http://localhost:5432