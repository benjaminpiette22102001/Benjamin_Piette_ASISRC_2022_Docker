FROM node:10.16-alpine

# Nous créons l'App Directory
RUN mkdir -p /usr/src/app
WORKDIR /usr/src/app

# Nous devons maintenant installer les dépendances 
COPY package*.json ./
COPY ./yarn.lock ./

RUN yarn install --silent

# Nous copions la source code de l'App
COPY . .

# Nous exportons
EXPOSE 5000

CMD ["yarn","start"]