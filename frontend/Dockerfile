
# Dockerfile for React client

# Build react client
FROM node:20.11.0-alpine3.19

# Working directory be app
WORKDIR /usr/src/app

COPY package*.json ./

###  Installing dependencies

RUN npm install

# copy local files to app folder
COPY ./public public
COPY ./src src

EXPOSE 3000

CMD ["npm","start"]