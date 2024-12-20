FROM python:2.7-alpine

RUN mkdir /app
WORKDIR /initgit 

COPY requirements.txt requirements.txt
RUN pip install -r requirements.txt

COPY . .

LABEL maintainer="WebMagic Informatica <info@webmagicinformatica.com>" \
      version="3.0"git