FROM node:18.5

WORKDIR /app/client

COPY package*.json ./

RUN npm install

COPY . .

CMD ["npm", "start"]