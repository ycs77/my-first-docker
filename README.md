# My First Docker Repo

## Develop

Start nginx server:

```
docker-compose up
```

Stop server:

```
docker-compose down
```

## Builded image

Build docker image:

```
docker build -t ycs77/my-first-docker .
```

Run the docker image:

```
docker run -d -p 8080:80 --name my-first-docker-ct ycs77/my-first-docker
```

Remove container:

```
docker rm my-first-docker-ct -f
```
