release: python3 manage.py migrate
web: gunicorn config.wsgi:application --preload --log-file -
