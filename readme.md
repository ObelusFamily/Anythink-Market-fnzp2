# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

---

## Setting up a local environment
### Backend Setup

1: Before we dive into the code, we need Docker. It’s going to make it easier for us to run things locally, which we’ll have to do a lot during your work here. So first thing’s first - [install Docker](https://docs.docker.com/get-docker/).

2: You can verify docker is ready by running the following commands in your terminal: `docker -v` and `docker-compose -v`.

3: Then, run `docker-compose up` from the project root directory to load Anythink's backend and frontend.

4: If Docker is working correctly, the backend should be running and able to connect to your local database.

- Let's test this by pointing your browser to http://localhost:3000/api/ping

### Frontend Setup

1: Now, it’s time to check the frontend and make sure it’s connected to the backend.

2: If everything is working properly, you’ll be able to create a new user on http://localhost:3001/register

3: Just make sure that you run all scripts in the next quests on one of the containers created by docker-compose up.  Also, you can use docker exec to run commands on a running container.

` It looks like your environment is ready! 😀 `