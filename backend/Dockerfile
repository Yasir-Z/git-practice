FROM node:20.20-slim

WORKDIR /app

COPY package.json .

RUN npm install 

COPY . . 

CMD ["node", "app.js"]
