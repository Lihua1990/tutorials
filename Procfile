release: flask db upgrade
web: gunicorn -b 0.0.0.0:$PORT mytutorials:autoapp --log-file - 
