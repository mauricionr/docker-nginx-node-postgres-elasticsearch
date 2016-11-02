FROM node:7.0

RUN mkdir /src

RUN npm install -g nodemon

# Define working directory
WORKDIR /src
RUN npm install

# Expose port
EXPOSE  8080

# Run app using nodemon
CMD ["nodemon", "/src/index.js"]