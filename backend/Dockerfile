FROM node:20.11.0-alpine3.19

WORKDIR /usr/src/app

COPY package*.json ./

RUN npm install

COPY ./src/app.js ./src/

EXPOSE 5000

CMD ["npm", "start"]