# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup
1. Install docker: https://docs.docker.com/get-docker/
2. Verify your installation:
```shell
docker -v
docker-compose -v
```

## Run code
```shell
docker-compose up
```

## Create a new user
1. Go to http://localhost:3001/register
2. Fill the form and verify that the newly registered user is logged in