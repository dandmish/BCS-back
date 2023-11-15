FROM python:3.12.0a3-slim-buster

COPY . /app

RUN pip install -r /app/requirements.txt

EXPOSE 8000

CMD python /app/manage.py runserver 0.0.0.0:8000 --noreload