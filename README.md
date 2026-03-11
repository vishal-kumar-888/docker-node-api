# Docker Node API

Simple Node.js API running inside Docker.

## Tech Stack

- Node.js
- Docker
- Git

## Run locally

npm install
node src/server.js

## Run with Docker

docker build -t docker-node-api .

docker run -p 3000:3000 docker-node-api