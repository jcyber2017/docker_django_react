# docker_django_react
This repository is to show one way to work with Docker, Django, Nginx and ReactJS

This project serves as an example of a deployment frontend (ReactJS) and backend (Django) using Docker and Nginx.

How to run
Make sure you have docker and docker-compose installed and run

inside folder backend create a file: .env in this file add this line:
SECRET_KEY=YOUR_SECRET_KEY

docker-compose -f docker-compose-dev.yml up
