FROM node:10

# Create app directory
WORKDIR /user/app

# Install app dependencies
COPY package*.json ./
# RUN npm install

# Bundle app source
COPY . .

EXPOSE 4000
CMD [ "npm", "start"]