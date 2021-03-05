
### Running the Application Locally

1. Install Node.js and MongoDB on your dev box

1. Execute 'mongod' to start the MongoDB daemon if it's not already running

1. Install Nodemon: `npm install nodemon -g`

1. Open `config/config.development.json` and change the host from `mongodb` to `localhost`

1. Run `npm install` to install app dependencies

1. Run `npm start` to compile the TypeScript and start the server

1. Browse to http://localhost:3000

## Running the Application with Docker

1. Install Docker for Mac/Windows or Docker Toolbox - https://www.docker.com/products/overview

1. Open a command prompt window

1. Run `npm install`

1. Run `npm run tsc:w` to compile TypeScript to JavaScript locally (leave the window running). This is only needed when in "dev" mode.

1. Open another command window and navigate to this application's root folder in the command window

1. Run `docker-compose build` to build the images

1. Run `docker-compose up` to run the containers

1. Navigate to http://localhost:3000 if using Docker for Mac/Windows or http://192.168.99.100:3000 if using Docker Toolbox in a browser

1. Live long and prosper

