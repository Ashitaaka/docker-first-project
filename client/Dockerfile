FROM node:lts-alpine

RUN mkdir /app
WORKDIR /app
COPY package*.json ./
RUN npm i
COPY src src
COPY public public
COPY *.config.* ./

CMD npm start