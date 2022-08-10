FROM node:16
WORKDIR /usr/src/app
COPY package*.json ./
copy . .
RUN npm install
EXPOSE 8080
CMD [ "npm", "start" ]
