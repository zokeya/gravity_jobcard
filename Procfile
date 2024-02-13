web: gunicorn application:application --workers=4 --worker-class=uvicorn.workers.UvicornWorker
web: uvicorn application:application --host=0.0.0.0 --port=$PORT
