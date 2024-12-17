FROM node:lts-alpine

WORKDIR /client
COPY package*.json ./
RUN npm i
COPY vite.config.js ./
COPY public public
COPY index.html index.html
COPY src src

CMD npm run dev --host