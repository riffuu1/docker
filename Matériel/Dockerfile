FROM node:22-alpine

WORKDIR /app

COPY package*.json ./

RUN ls -l /app/package.json

RUN npm install

COPY . .

EXPOSE 3000

CMD ["node", "index.js"]