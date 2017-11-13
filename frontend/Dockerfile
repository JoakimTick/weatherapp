FROM node:latest
ADD / /usr/backend/
WORKDIR /usr/backend
RUN npm install
EXPOSE 8000

CMD [ "npm", "start" ]
