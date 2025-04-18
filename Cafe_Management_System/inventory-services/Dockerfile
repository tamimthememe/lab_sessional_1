FROM node:18

WORKDIR /app/inventory

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 3002


CMD ["node", "index.js"]
