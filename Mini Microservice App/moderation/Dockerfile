FROM node:lts-alpine3.9

WORKDIR /app

COPY ./package.json ./
RUN npm install
COPY ./ ./

CMD [ "npm", "start" ]