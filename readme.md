# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. install docker (https://docs.docker.com/get-docker/)
2. run `docker-composer up` in the root of the cloned repo.
3. verify all works by trying http://localhost:3000/api/ping
4. register new user using http://localhost:3001/register
