# syntax=docker/dockerfile:1

FROM node:18-alpine

WORKDIR /front_end
COPY . .
RUN npm install

EXPOSE 4200
CMD [ "node_modules/.bin/ng", "serve", "--host", "0.0.0.0", "--port", "4200" ]
