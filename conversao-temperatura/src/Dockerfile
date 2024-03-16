FROM node:18.16.0
WORKDIR /ap
COPY package*.json ./
RUN npm install
COPY . .
EXPOSE 8080
CMD ["node", "server.js"]
