# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. You need to have docker installed on your system. You can refer the [steps here](https://docs.docker.com/get-docker/) according to your machine.
2. You can verify if Docker was properly installed by running the command `docker -v`.
3. After verification, navigate to the root directory of the project and run `docker-compose up`. 
   You can test it's working by [pointing here](http://localhost:3000/api/ping).
4. Once that is done, you can make sure that the frontend is connected to the backend by creating a new user [here](http://localhost:3001/register).


