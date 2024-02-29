# image Python officielle
FROM python:3.8-slim

# répertoire de travail
WORKDIR /app

# Copie app code 
COPY . /app

# installation des dépendances
RUN pip3 install --no-cache-dir -r requirements.txt

# port 80
EXPOSE 80

# run application
CMD ["flask", "run", "--host=0.0.0.0", "--port=80"]
