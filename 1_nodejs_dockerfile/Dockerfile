FROM node:19-alpine

# Copy local file and folder to /app - gets created in the container if it does not exist
COPY package.json /app/
COPY src /app/

# Change the container working directory to /app
WORKDIR /app

RUN npm install

# Runs this command upon running a container using image created in this Dockerfile
CMD ["node", "server.js"]