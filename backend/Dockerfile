# syntax=docker/dockerfile:1
FROM node:20-alpine3.18

RUN addgroup app && adduser -S -G app app
USER app

WORKDIR /app

COPY package*.json /app/

RUN npm ci

COPY . /app/

EXPOSE 3001

CMD ["npm", "run", "dev"]
