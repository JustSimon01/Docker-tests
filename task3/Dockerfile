FROM node:16-alpine

WORKDIR /home/ilovedocker/app

COPY packages/package*.json ./

COPY ./src/* ./

RUN npm i

COPY . .

EXPOSE 3032

ENTRYPOINT ["node", "main.js"]
