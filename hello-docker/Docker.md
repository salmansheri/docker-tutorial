## Docker 

```Dockerfile
FROM node:20-alpine

  

WORKDIR /app

  

COPY . .

  

CMD node hello.js
```


## To build docker 

```bash
sudo docker build -t hello-docker .
```

## To run docker 

```bash
sudo docker run -it hello-docker sh
```

or 

```bash
sudo docker run hello-docker

```


