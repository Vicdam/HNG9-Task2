# pull the official base image
FROM node:current-alpine

# set work directory
WORKDIR /frontend

# install dependencies
COPY package*.json ./
RUN npm install

# copy project
COPY . .

CMD ["npm", "start"]