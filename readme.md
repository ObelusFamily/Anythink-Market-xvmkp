# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

- Clone the repository into your local filesystem

- Install [Docker](https://docs.docker.com/get-docker/). To verify Dockey is installed, run the following commands in your terminal `docker -v` and `docker compose up`

- Set the repository as the working directory and run `docker compose up`

- Test the backend is running going to [this page](http://localhost:3000/api/ping)

- Test the frontend is running by creating a new user in [this page](http://localhost:3001/register)
