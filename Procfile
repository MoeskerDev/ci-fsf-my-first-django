web: gunicorn django_django_first.wsgi:application --log-file - --log-level debug
python manage.py collectstatic --noinput
manage.py migrate