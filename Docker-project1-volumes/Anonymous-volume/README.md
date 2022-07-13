# Docker Commands

## build the app

```
docker build -t feedback-node .
```

## To login to DockerHub Registry via the Command line
```
docker login --username muluhmunu
```
## To push an image from your local to Docker Hub
```
docker push muluhmunu/feedback-node:tagname
docker push muluhmunu/feedback-node:v2
```
## To run the container or the microservice application,do
```
docker run -p 3000:80 --name feedback-app -d muluhmunu/feedback-node:v2
```
docker run -p 3000:80 --name feedback-app -d image-name:tag
```




muluhmunu/feedback-node
