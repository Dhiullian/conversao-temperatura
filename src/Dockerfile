FROM node:14.17.5
WORKDIR /appication
COPY package*.json ./
RUN npm i
COPY . .
EXPOSE 8080
CMD ["node", "server.js"]