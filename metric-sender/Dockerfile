FROM python:3.8.12-slim-buster
WORKDIR /app
COPY . .
RUN pip install -r metric-sender/requirements.txt
CMD ["python3", "-m", "metric-sender.app"]