# Dockerfile
### Tor
```shell_session
$ docker build -t tor dockerfile #Build
$ docker run -ti --rm -p 9050:9050 tor #Run
$ docker run -d -p 9050:9050 tor #Run
```
