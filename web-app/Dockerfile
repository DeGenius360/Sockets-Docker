FROM python:3.6.5

WORKDIR /app
COPY app.py .
COPY templates templates/
COPY static static/
COPY requirements.txt .

RUN pip3 install -r requirements.txt