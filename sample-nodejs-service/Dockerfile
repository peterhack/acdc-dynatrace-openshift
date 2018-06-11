FROM node:carbon
WORKDIR /usr/srv/app
COPY package*.json ./
RUN npm install
COPY app.js app.js
COPY index.html index.html
EXPOSE 8080
CMD [ "npm", "start"]
