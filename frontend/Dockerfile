FROM node:latest
ADD / /usr/frontend/
WORKDIR /usr/frontend
RUN npm install
EXPOSE 8000

CMD [ "npm", "start" ]
