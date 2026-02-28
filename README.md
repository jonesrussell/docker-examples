# Docker Examples

Companion code for the [Docker Fundamentals](https://jonesrussell.github.io/blog/) blog series.

## Structure

Each folder corresponds to a post in the series:

| Folder | Post | Description |
|--------|------|-------------|
| `01-dockerfile-basics/` | [Writing Your First Dockerfile](https://jonesrussell.github.io/blog/docker-dockerfile-fundamentals/) | Dockerfile fundamentals — FROM, COPY, RUN, CMD |
| `02-multi-stage-builds/` | Coming soon | Multi-stage builds for smaller images |
| `03-docker-compose/` | Coming soon | Docker Compose basics |

## Getting Started

```bash
git clone https://github.com/jonesrussell/docker-examples.git
cd docker-examples/01-dockerfile-basics
docker build -t hello-docker .
docker run -p 3000:3000 hello-docker
```

Then open http://localhost:3000 to see it running.

## Requirements

- [Docker](https://docs.docker.com/get-docker/) installed
- Basic terminal/command line knowledge

## License

MIT
