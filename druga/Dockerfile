# syntax=docker/dockerfile:1

FROM python:3.8-slim-buster


WORKDIR /app2-docker

COPY . .

RUN pip3 install -r requirements.txt

EXPOSE 5060

CMD ["python3", "drugi.py"]
