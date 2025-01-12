to build docker image from dockerfile run: `docker build -t image-name:image-version .` with image name being something like node-server and the version being something like 1.0

to run local docker container and bind port to same host port (in this case, 3000) run `docker run -d -p 3000:3000 node-server:1.0`. remember the formatting of port binding in general is host-port:container-port
