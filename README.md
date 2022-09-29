# recipe-app-api
Recipe API Project

## Docker
### docker build the images defined by Dockerfile
docker build .
### run first time to docker-compose build the services inside docker-compose.yml
docker-compose build    

### run after make changes in docker-compose.yml and start the docker to run the app and services
docker-compose up

## Flake8
docker-compose run --rm app sh -c "flake8"

## Test
docker-compose run --rm app sh -c "python manage.py test"