FROM node:alpine

WORKDIR usr/src/app

COPY ../node-hello-world .

RUN npm install

EXPOSE 3000

CMD ["npm", "run", "start"]
