FROM python:3.9


RUN mkdir /api && apt-get update
WORKDIR /api

COPY requirements.txt requirements.txt
RUN python -m pip install -r requirements.txt

COPY ./ /api