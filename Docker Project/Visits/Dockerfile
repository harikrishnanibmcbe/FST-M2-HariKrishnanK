#specify base image
FROM node:18-alpine

#Create a working directory
WORKDIR /usr/app

#Copy package.json file to container
COPY package.json /usr/app

#Install dependencies
RUN npm install

#Copy all other files to container
COPY ./ /usr/app

#Start the browser
CMD ["npm", "start"]
