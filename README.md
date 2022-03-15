# PYTHON FLASK RESTFUL API
## starter repo to build and run a simple Flask RESTful API via docker container

Clone repo `git clone https://github.com/TWalstrom/python-flask-restful-api.git

Chande directory `cd restful-api-python-flask`

Build image `docker build -t restful-api .` 
  
Run container in detached mode and publish port 5000 `docker run -d -p 5000:5000 restful-api`
  
API should be accessible on port 5000 `curl -i localhost:5000/todo/api/v1.0/tasks`
