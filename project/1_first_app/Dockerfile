# pull base image for python
FROM python:3.8-slim

# set work directory
WORKDIR /app

# copy files to app folder
# . current working directory = 1_first_app
COPY . /app
# or copy app.py/app
CMD ["python", "app.py"]