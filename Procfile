web: gunicorn --access-logfile=- --bind=0.0.0.0:$PORT --forwarded-allow-ips='*' project.wsgi:application
release: python manage.py migrate --noinput