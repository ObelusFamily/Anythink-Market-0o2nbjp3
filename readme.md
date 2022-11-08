# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

Install Docker. it could be found here: https://docs.docker.com/get-docker/
You can verify docker is ready by running the following commands in your terminal: docker -v and docker-compose -v.

Then, run docker-compose up from the project root directory to load Anythink's backend and frontend.

## Check that your docker enviroment is up and running
First, run docker-compose up from the project root directory to load Anythink's backend and frontend.
Once it's done - you can check that it was done correctly by copying the following to your browsers' url line:

For the BackEnd: http://localhost:3000/api/ping
For the FrontEnd: http://localhost:3001/register

You can then set up a new user on the FrontEnd, to make sure the db is running and connected properly as well.
Good luck!