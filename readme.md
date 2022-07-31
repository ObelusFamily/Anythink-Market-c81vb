# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. Once docker is installed, verify by using the docker -v, and docker-compose -v commands.
2. Next, navigate to your root directory, and run docker-compose up
3. If successful, clicking this link should work for the backend: http://localhost:3000/api/ping
4. You can verify the front end works if you can make an account here: http://localhost:3001/register
5. You're all set.