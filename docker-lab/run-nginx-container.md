# Running an Nginx Container

## Pull Image

```bash
sudo docker pull nginx
```

## Start Container

```bash
sudo docker run -d --name webserver -p 8080:80 nginx
```

## Verify Running Container

```bash
sudo docker ps
```

## Access From Windows

Open:

http://<Ubuntu-IP>:8080

The default Nginx welcome page confirmed that the container was reachable from the Windows host.

## Container Lifecycle Commands

```bash
sudo docker stop webserver
sudo docker start webserver
sudo docker rm webserver
```
