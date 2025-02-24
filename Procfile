web: gunicorn config.wsgi:application --log-file -

web: daphne -b 0.0.0.0 -p $PORT config.asgi:application
