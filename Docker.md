
### - check docker version
```
$ docker --version
```

### - docker info
```
$ docker info
```

### - docker hub login
```
$ docker login
```

### - docker sample project
```
$ docker run hello-world
// it will download from remote repo if it doesn't exist locally
```

### - list of image files
```
$ docker image ls
```

### - remove image file
```
$ docker image rm IMAGE_ID
```

### - build app
```
$ docker build --tag=firsthello .
```

### - run app
```
$ docker run -p 4000:80 firsthello
```

### - check all containers
```
$ docker container ls --all
```

### - list of running containers
```
$ docker container ls
```

### - tag for docker hub
```
$ docker tag image username/repository:tag
// docker tag firsthello mkhan07/firsthello:v0.0.0
```

### - pushing to docker hub
```
$ docker push username/repository:tag
// docker push mkhan07/firsthello
```
