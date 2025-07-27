FROM node
WORKDIR /app
COPY package*.json ./
RUN npm install express
COPY . .
EXPOSE 5001
WORKDIR /app/src
CMD ["node","server.js"]