# Основной веб-сервер (Flask + Gunicorn с 4 воркерами)
web: gunicorn --bind 0.0.0.0:$PORT --workers 4 --threads 2 --timeout 120 app:app