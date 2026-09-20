FROM node:22.18.0-alpine

WORKDIR /app

COPY package.json ./

RUN npm install --production

COPY . .

EXPOSE 3002

CMD ["node", "app.js"]