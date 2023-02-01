# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

## Setting Up the Project

1. install docker from the [docker official website](https://docs.docker.com/get-docker/)
2. verify that docker is ready by running the following commands in your terminal

```
docker -v
```

and

```
docker-compose -v
```

3. run `docker-compose up` from the project root directory to load Anythink's backend and frontend.
4. if Docker is working correctly, the backend should be running and able to connect to your local database. Test this by pointing your browser to http://localhost:3000/api/ping
5. now let's check the frontend. Let's check the frontend if it's connecting properly with the backend. If everything is working properly, you’ll be able to create a new user on http://localhost:3001/register. Create one (choose a cool nickname and everything) and you’ll be able to move to the next task.

With this all is set to go.
