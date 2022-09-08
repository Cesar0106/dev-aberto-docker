# syntax=docker/dockerfile:1

FROM python:3.8-slim-buster

WORKDIR /~/Desktop/desenvolvimento_aberto/aulas/aula_5/ProjetoProfissional/src
ENV FLASK_APP=softdes.py
COPY requirements.txt requirements.txt
RUN pip3 install -r requirements.txt

COPY . .

CMD [ "python3", "-m" , "flask", "run", "--host=0.0.0.0"]