FROM node:20.11.0-alpine3.19

WORKDIR /usr/src/app

COPY package*.json ./

RUN npm install

COPY ./public public
COPY ./src src

EXPOSE 3000

CMD ["npm","start"]