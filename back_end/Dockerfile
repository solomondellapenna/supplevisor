# syntax=docker/dockerfile:1

FROM node:18-alpine

WORKDIR /back_end

COPY . /back_end

RUN npm install

RUN npm i --save-dev dotenv nodemon

EXPOSE 3000

CMD ["npm", "run", "devStart"]