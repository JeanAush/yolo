# Build stage
FROM node:18.19.1-alpine 
WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . .
RUN npm install
EXPOSE 5000
CMD ["node", "server.js"]

