FROM node:latest
WORKDIR /usr/weatherapp/backend
COPY package.json /usr/weatherapp/backend
RUN npm install
EXPOSE 9000

CMD [ "npm", "start" ]
