# Go Server with Docker

This repository contains a simple Go server implementation that can be run inside a Docker container. The server listens on port 8080 and responds with an HTML message when accessed.

Prerequisites

Docker installed on your system

Getting Started

To get started with this project, follow the steps below:

Clone this repository to your local machine:

git clone https://github.com/your-username/go-docker.git

Build the Docker image:

docker build -t go-docker .

Run the Docker container:

docker run -d -p 8080:8080 go-docker

Access the server in your web browser by visiting http://localhost:8080.
