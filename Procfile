release: flask db upgrade
web: gunicorn -b 0.0.0.0:$PORT mytutorials.app:create_app() --log-file - 
