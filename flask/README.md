
BUILD CMD :

$ docker build -t simple-flask-app:latest

RUN IN CONTAINER CMD:

$ docker run -d -p 5000:5000 simple-flask-app

Application will run at : http:127.0.0.1:5000
