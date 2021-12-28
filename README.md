# recipe-app-api
Recipe App API


docker-compose run app sh -c "django-admin.py startproject core"

# creates user
docker-compose run --rm app sh -c "python manage.py startapp user"

docker-compose run app sh -c "python manage.py makemigrations core"
docker-compose run app sh -c "python manage.py startapp core"
docker-compose run app sh -c "python manage.py test"

TO RUN TESTS:
docker-compose run app sh -c "python manage.py test && flake8"

TO RUN Server:
docker-compose up

unit tests:
docker-compose run app sh -c "python manage.py test"


Jenkins builds -- video 36
