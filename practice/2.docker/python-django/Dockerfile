FROM python:3.9@sha256:bf508488fa1a287313bba9e4969318b1b00cf4921055dcf10996a096c28afd67

RUN pip install Django==3.2

ADD . /app

EXPOSE 8000

ENTRYPOINT python /app/manage.py runserver 0.0.0.0:8000
