# recipe-app-api
# Docker Commands
-- docker-compose build
-- docker-compose up
-- docker-compose down
-- docker-compose run --rm app sh -c "python manage.py test"
-- docker-compose run --rm app sh -c "python manage.py wait_for_db && python manage.py migrate"
-- docker-compose run --rm app sh -c "python manage.py makemigrations"