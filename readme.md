# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. [Install Docker](https://docs.docker.com/get-docker/)
2. Verify that Docker is installed successfully by using the terminal commands 
  - `docker -v`
  - `docker compose -v`
3. Clone the Git repository using the command
  - `git clone <github repo address>`
4. From the cloned repository's root directory, start the docker container using the command
  - `docker compose up`
5. Test that the container is up and running by pointing your [browser here](http://localhost:3000/api/ping)
6. Once you have verified that it is up and running, [Register a new user](http://localhost:3001/register)
