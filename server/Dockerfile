FROM node:lts-alpine

RUN mkdir /server
WORKDIR /server
COPY package*.json ./
RUN npm i
COPY src src

CMD npm start