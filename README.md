# recipe-app-api
Recipe App API






docker-compose run app sh -c "django-admin.py startproject core"


docker-compose run app sh -c "python manage.py makemigrations core"
docker-compose run app sh -c "python manage.py startapp core"
docker-compose run app sh -c "python manage.py test"


unit tests:
docker-compose run app sh -c "python manage.py test"
