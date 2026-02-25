web: gunicorn bookstore.wsgi

web: python manage.py migrate && python create_admin.py && python manage.py collectstatic --noinput && gunicorn bookstore.wsgi