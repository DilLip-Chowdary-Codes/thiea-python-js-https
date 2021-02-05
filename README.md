# Build Customized IDE using theia

## Build Docker Image :

```
docker build . -t theia-customized-ide
```

## Run Your IDE in Container :

### docker-compose: 

```
 docker-compose up -d
```
   (or)
   
### docker run

```
docker run --init -it -p 8000:10443 -p 8080:8080 -e token=s3cr3t -v "$(pwd)/Workspace:/home/Workspace" theia-customized-ide
```


If you have any Queries Drop Here :  [Discussions](https://github.com/DilLip-Chowdary-Codes/thiea-python-js-https/discussions)
