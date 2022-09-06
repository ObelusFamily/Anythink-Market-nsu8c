# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

# Step 1: Install Docker

You can verify docker is ready by running the following commands in your terminal:
...

docker -v
docker-compose -v
...

# Step 2: Run Docker

Run following command from the project root directory to load Anythink's backend and frontend.
...

docker-compose up
...

if Docker is working correctly, the backend should be running and able to connect to your local database.

# Step 3: Check if backend is connected to your local database

Test this by pointing your browser to http://localhost:3000/api/ping
