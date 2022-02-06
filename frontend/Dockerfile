# Création du client 
FROM node:10.16-alpine

# Working directory de l'App
WORKDIR /usr/src/app

COPY package*.json ./
COPY ./yarn.lock ./

###  Installation des dépendances 
RUN yarn install --silent

# copier les fichiers locaux dans le dossier de l'application
COPY . .

EXPOSE 2000

CMD ["yarn","start"]