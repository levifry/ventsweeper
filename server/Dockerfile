# What image do you want to start building on?
FROM node:alpine

# Make a folder in your image where your app's source code can live
WORKDIR /server

# Tell your container where your app's source code will live
# RUN mkdir -p /app

# What source code do you what to copy, and where to put it?
COPY . /server

# Does your app have any dependencies that should be installed?
RUN npm install

# What port will the container talk to the outside world with once created?
EXPOSE 3001

# How do you start your app?
CMD ["npm", "start"]