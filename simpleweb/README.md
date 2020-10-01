- Build docker image tag

```
docker build -t <USERNAME>/<IMAGENAME>:<VERSION> .
```

eg

```
docker build -t amitad16/simpleweb .
```

- Run container

```
docker run -p 8080:8080 <USERNAME>/<IMAGENAME>
```

eg

```
docker run -p 8080:8080 amitad16/simpleweb
```
