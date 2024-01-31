FROM node:20.11.0-alpine3.19

WORKDIR /usr/src/app

COPY package*.json ./

RUN npm install

EXPOSE 5000

CMD ["npm", "run", "watch"]