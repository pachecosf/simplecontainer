# Simple Container

This is a simple container to learn how to containerize go code

### Prerequisites

What things you need to install the software and how to install them

```
Docker
```

### Installing

Build the docker image and give it a tag

```
 docker build -t <TAGNAME> ./internal/main/.
```

Run a container for the docker image and map it's port to 80

```
docker run -d -p 80:80 <TAGNAME>
```

Check that the docker container is running using 

```
docker ps
```

Connect to https://localhost:80 to see if your container is working

