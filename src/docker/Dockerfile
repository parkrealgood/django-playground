FROM python:3.9

MAINTAINER parkgood1020 <parkgood1020#gmail.com>

RUN pip3 install django

WORKDIR /usr/src/app

COPY ../.. .

WORKDIR ./conf

CMD ["python3", "manage.py", "runserver", "0.0.0.0:8009"]

EXPOSE 8009
