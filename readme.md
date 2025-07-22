## Setup

1. Start container with `docker compose up -d`.

2. SSH into container. pwd should show `/home/node/app`.

3. Create a react app with `npx create-react-app my-react-app`. Takes about 2 mins.

4. Cd to my-react-app and run app with `npm start`. It should be served at http://localhost:3000. You can edit code and it will be refreshed automatically in the browser.

## Sources

https://www.docker.com/blog/how-to-dockerize-react-app/