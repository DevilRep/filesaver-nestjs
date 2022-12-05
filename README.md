# Filesaver

This is a simple file store project like Google drive. The main purpose of this project is try a new technologies, frameworks, etc

# Technologies

* nestjs
* postgresql

# Prerequirements

You should have installed `docker` and `docker-compose` to run this project in a docker container or `nodejs` and `nestjs` to run it without container

# Installation

This step is requred only for non-docker run. Run the command `yarn` to install all depenencies

# Run the app

## Using docker

Run the command `docker-compose up` to start the project in a container

## Without docker

You also can run this project without a docker by using a command `yarn start` to start the project in standart mode or `yarn start:dev` to run the project in dev mode (with autorestart) or `yarn start:debug` to run the project in debug mode (also with autorestart)

 # Tests

 Run the command `npm run test` for unit tests

For e2e tests can be used the command `npm run test:e2e`

 # License

 [Apache](https://choosealicense.com/licenses/apache-2.0/)