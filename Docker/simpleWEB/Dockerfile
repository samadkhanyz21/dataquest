# Specify a base image
FROM node:19-alpine

WORKDIR /usr/app

# Install some dependencies
COPY ./ ./
RUN npm install

# Default Command
CMD ["npm", "start"]