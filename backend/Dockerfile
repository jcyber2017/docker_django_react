# docker/backend/Dockerfile
FROM python:3.9.1

# set environment variables
ENV PYTHONDONTWRITEBYTECODE 1
ENV PYTHONUNBUFFERED 1

WORKDIR /app
ADD ./requirements.txt /app/backend/

RUN pip install --upgrade pip
RUN pip install gunicorn
RUN pip install -r /app/backend/requirements.txt

# ADD ./docker /app/docker
ADD ./ /app/backend
