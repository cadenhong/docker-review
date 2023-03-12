FROM node:13-alpine

# Environment variables can be set here, but recommended to do so in Docker Compose file
ENV MONGO_DB_USERNAME=admin \
    MONGO_DB_PWD=password

COPY . /home/app/

WORKDIR /home/app/

RUN npm install

EXPOSE 3000

CMD [ "node", "server.js"]