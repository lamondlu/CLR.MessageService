# Docker configuration
This markdown is just for how to create image and container for CLR.MessageService

## Create Image
```
docker build -t clr.messageservice.webapi:v1 -f dockerfile.webapi .
```


## Create Container

```
docker run -d -p 5000:80 --name myapi clr.messageservice.webapi:v1
```