# image Node.js v12 Alpine officielle
FROM node:12-alpine

# répertoire de travail
WORKDIR /app

# copy app code 
COPY . /app

# installation des dépendances
RUN npm install

# port 80
EXPOSE 80

# Lance le script d'initialisation
CMD ["npm", "start"]


