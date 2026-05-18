# Mindustry

ok... technically *not* Mindustry. This contains dockerfiles for Mindustry server containers.

## Usage

### Docker

1. `docker pull bndlett/mindustry:latest`
2. `docker run bndlett/mindustry:latest -d -it`

From there, you can attach to the terminal. No environment variables are available.

### Building

-# (this is mostly just for self-reference)
`docker build . -t name:tag .`
