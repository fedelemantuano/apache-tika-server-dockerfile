# apache-tika-server-dockerfile

**apache-tika-server-dockerfile** is a dockerfile to build [fmantuano/apache-tika-server](https://hub.docker.com/r/fmantuano/apache-tika-server/) Docker image.


To use it, create a new instance as usual:

```
$ sudo docker run --name apache-tika-server -d -p 9998:9998 fmantuano/apache-tika-server
```

Once the docker instance is created, you can control it by running:

```
$ sudo docker start apache-tika-server

$ sudo docker stop apache-tika-server
```

To exec an interactive shell:

```
$ sudo docker exec -ti apache-tika-server /bin/bash
```
