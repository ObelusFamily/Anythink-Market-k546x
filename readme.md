# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

install docker from [here]([https://docs.docker.com/get-docker/]) 

To check the status of Docker on your local device, execute 'docker -v'
To check the status of Docker-compose on your local device, execute 'docker-compose -v'

To start the app, execute 'docker-compose up' from the root directory of the repo.

If Docker is working correctly, the backend should be running and able to connect to your local database.
Use http://localhost:3000/api/ping to check if the backend is running.

Check the front-end by navigating to http://localhost:3001/register and creating a new user.

You are now set up to start the app!
