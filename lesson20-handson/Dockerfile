FROM python:3.9-slim

WORKDIR /app

COPY ./ /app

RUN pip install -r requirements.txt

EXPOSE 8080

ENTRYPOINT ["python", "/app/hello-world.py"]
