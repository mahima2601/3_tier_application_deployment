FROM node:14

WORKDIR /app

Copy package*.json ./

RUN npm install

COPY . .

CMD ["npm", "start"]

