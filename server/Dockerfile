FROM node:18-alpine3.15

# Create app directory  
WORKDIR /usr/src/app
COPY package*.json ./

# Install app dependencies
RUN npm install
COPY . .
EXPOSE 8080
CMD [ "npm", "start" ]