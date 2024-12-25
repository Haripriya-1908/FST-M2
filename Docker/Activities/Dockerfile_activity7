# Specify Base Image
FROM docker.io/node:18-alpine

# create Work Directory
WORKDIR /usr/app

#copy the package.json to /usr/app
COPY package.json ./

# Install required software
RUN npm install

#Copy the other files
COPY ./ ./

# Set the starting Command
CMD ["npm" , "start"]
