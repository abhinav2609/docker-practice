# specify a base image
FROM node:14-alpine

WORKDIR /usr/app

#Install some dependencies
COPY ./package.json ./
RUN npm install
COPY ./ ./

#default command
CMD [ "npm", "start" ]