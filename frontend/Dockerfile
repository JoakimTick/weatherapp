FROM node:latest
ADD / /usr/backend/
WORKDIR /usr/backend
RUN nmp install
EXPOSE 8000

CMD [ "nmp", "start" ]
