web: python manage.py migrate
web: python manage.py runserver
web: gunicorn CCMS.wsgi --log-file -
heroku config:set DISABLE_COLLECTSTATIC=1