FROM python:3.10-slim

WORKDIR /app

# Instalar dependencias necesarias
RUN pip install --no-cache-dir flask pymongo

COPY . .

CMD ["python", "app.py"]