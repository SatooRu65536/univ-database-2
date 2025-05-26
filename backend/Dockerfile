FROM python:3.13-bullseye

WORKDIR /backend
COPY requirements.lock .
RUN pip install -r requirements.lock

ENTRYPOINT ["python", "manage.py", "runserver", "0.0.0.0:8000", "--settings", "config.settings.development"]
