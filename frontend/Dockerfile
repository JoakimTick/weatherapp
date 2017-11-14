FROM node:latest
WORKDIR /usr/weatherapp/frontend
COPY package.json /usr/weatherapp/frontend
RUN npm install
EXPOSE 8000

CMD [ "npm", "start" ]
