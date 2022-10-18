# creating a docker image

# this will fetch python 3.7 version from docker
FROM python:3.7

# . means copy all the files/folders present in this directory to /app
COPY . /app

# making /app as our work directory
WORKDIR /app

# this will run requirements.txt file and install all the applications
RUN pip install -r requirements.txt

# this will run file app.py
CMD ["python", "app.py"]
