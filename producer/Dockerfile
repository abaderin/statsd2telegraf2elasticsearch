FROM python:3

WORKDIR /app
COPY statsd-producer/requirements.txt /app
RUN pip3 install -r requirements.txt
COPY statsd-producer /app
CMD ["python3", "main.py"]