# syntax=docker/dockerfile:1
#base image
FROM python:3.7-alpine
#working directory
WORKDIR /code
#environment variables
ENV FLASK_APP=main.py
ENV FLASK_RUN_HOST=0.0.0.0

RUN apk add --no-cache gcc musl-dev linux-headers
#install dependencies
COPY requirements.txt requirements.txt
RUN pip install -r requirements.txt
EXPOSE 5000
#copy project
COPY . .
CMD ["flask" , "run"]