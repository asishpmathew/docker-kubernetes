FROM node:alpine

WORKDIR /usr/app

COPY ./package.json ./
COPY ./ ./
RUN npm install

CMD ["npm", "start"]