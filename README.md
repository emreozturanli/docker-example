# INSTRUCTIONS

Run below commands after downloading or cloning the repository.

Create a docker image by using the docker build command:
### `docker build -f Dockerfile.dev -t react-app .`

Create a docker container by running:
### `docker run -d -it --rm -p 3000:3000 --name react-app react-app`

Verify whether the container has been created successfully by running:
### `docker container ps`

Navigate to [http://localhost:3000](http://localhost:3000) in your browser to view the dockerized react app