# Git and Docker Starter Application

This repository contains a small Python web application used to practice Git, GitHub, and Docker workflows.

## Application

The application listens on port 8000 and returns a text response when accessed over HTTP.

## Verification

Verify the running application with curl or in a web browser using port 8000.

## Usage

Build the Docker image with:

docker build -t git-docker-app:test .

Run the application with:

docker run --rm -p 8080:8000 git-docker-app:test

Then access the application at http://localhost:8080.
