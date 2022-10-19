release: python manage.py migrate
web: gunicorn core.wsgi

web gunicorn core.wsgi:application --log-file -
