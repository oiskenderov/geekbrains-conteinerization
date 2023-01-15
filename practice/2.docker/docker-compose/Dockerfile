FROM python:3.6.8-jessie@sha256:3a8278cd7264fa12e91a1b896853a36cc61623f26a0acb22c5c55d5822317c65

ENV PYTHONUNBUFFERED 1

WORKDIR /app

ADD requirements.txt .
RUN pip install -r requirements.txt

ADD . .

CMD /bin/sh docker-entrypoint.sh
