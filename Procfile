web: gunicorn final.wsgi --log-file -
heroku config:set DISABLE_COLLECTSTATIC=1
web: python manage.py migrate
