# dockers
A kwonloadged base repo to store many docker files

# dependencies
## tools (you must provide the installation)
- [Docker](https://www.docker.com/)

# tests
- Comming soon ...

# dockers usage
Just grab any template dockerfile that you have interest, build and run
Sample:
```
curl -o Dockerfile.go.env https://raw.githubusercontent.com/rjansen/dockers/master/go/dev/Dockerfile
docker build -t go.dev -f Dockerfile.go.dev .
docker run -it --rm go.dev
```
