FROM node:23-alpine
// create a app
WORKDIR /app

COPY package*.json ./

RUN npm i

COPY . .

CMD ["node", "server.js"]
