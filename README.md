# mernGl
### Overview
This is a starter Express server created in local development in WSL 2 and docker.

This is just a backend started for now, can add code to extend backend functionality such as a datastore

And a front end can be added to create full stack app.

### Things to work on

- create nextjs 13 front end
- add routes to server
- connect to datastore
- docker compose to make it all work in docker
- secure routes
- publish to production server


### RUN

1. build image with docker file. [^1]
[^1]: docker build -t test:latest .
2. Run in docker container [^2]
[^2]: docker run -d --name test-container -p 127.0.0.1:3001:3001 test:latest
3. Go to localhost:3001 on web browser.
