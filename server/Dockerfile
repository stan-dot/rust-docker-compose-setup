FROM registry.hub.docker.com/library/node:22-bookworm as base
RUN apt-get update && export DEBIAN_FRONTEND=noninteractive && apt-get -y install git

# "image": "registry.hub.docker.com/library/node:22-bookworm",

COPY . /app
