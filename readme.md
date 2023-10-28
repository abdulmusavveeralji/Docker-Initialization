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

h1: part 2

```
docker run -it --name container_name image_name
docker run -it image_name
```

```
docker network inspect bridge
docker network ls
```

```
docker run -it --network=host image_name
docker run -it --network=none image_name
```

```
docker network create -d bridge youtube
docker network ls
docker run -it --network=youtube --name container_name image_name
```

```
docker network inspect youtube
```

Volumn mapping

```
docker run -it -v host_folder_path:remote_folder_path image_name
```
