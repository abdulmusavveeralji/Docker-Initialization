```
docker run -it ubuntu
```

```
docker container ls
docker container ls -a
```

```
docker start container_name
docker stop container_name
```

```
docker exec container_name ls
docker exec -it container_name ls
```

```
docker images
```

```
docker run -it -p 1025:1025 image_name
```

```
docker build -t container_name .
```

```
docker exec -it container_id bash
```

```
docker run -it -e PORT=4000 -p 4000:4000 image_name
```
