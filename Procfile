web: cd ekip && python manage.py migrate --settings=config.settings.production --noinput && python manage.py collectstatic --settings=config.settings.production --noinput && waitress-serve --port=$VCAP_APP_PORT config.wsgi:application