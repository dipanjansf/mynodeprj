# mynodeprj

### Build project with docker!
```
$ docker build -t cdipanjan/mynodeproj:1.1 .
```

### See the Built image
```
$ docker images
```

### Run the Dockerfile to create a container
```
$ docker run -p 85:8081 --name mynodejs1 cdipanjan/mynodeproj:1.1
```

### Access the App from Web!
```
http://localhost:8081/
```
