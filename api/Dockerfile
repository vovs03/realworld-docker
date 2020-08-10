FROM node:13

WORKDIR /usr/src/app

COPY package*.json ./

# install npm-packages
RUN npm install
COPY . .