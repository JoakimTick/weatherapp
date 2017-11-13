FROM node:latest
ADD / /usr/backend/
WORKDIR /usr/backend
RUN npm install
EXPOSE 9000

CMD [ "npm", "start" ]
