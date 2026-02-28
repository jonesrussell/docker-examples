# Part 1: Dockerfile Basics

A minimal Express server to demonstrate Dockerfile fundamentals.

## Blog Post

[Writing Your First Dockerfile](https://jonesrussell.github.io/blog/docker-dockerfile-fundamentals/)

## Build and Run

```bash
# Build the image
docker build -t hello-docker .

# Run the container
docker run -p 3000:3000 hello-docker
```

Visit http://localhost:3000 to see the response.

## Files

- `Dockerfile` — The container definition
- `.dockerignore` — Files excluded from the build context
- `package.json` — Node.js dependencies
- `index.js` — The Express server

## What You'll Learn

- `FROM` — Choosing a base image
- `WORKDIR` — Setting the working directory
- `COPY` — Adding files to the image
- `RUN` — Installing dependencies
- `EXPOSE` — Documenting the port
- `CMD` — Defining the startup command
