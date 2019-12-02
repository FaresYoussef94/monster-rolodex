#Specify the base image
FROM node:alpine

#Install dependency 
WORKDIR /usr/app

COPY ./package.json ./

RUN npm install

COPY ./ ./

#Default command
CMD ["npm","start"]