**problem**
```shell
permission denied while trying to connect to the Docker daemon socket
at unix:///var/run/docker.sock: Get "http://%2Fvar%2Frun%2Fdocker.sock/_ping":
dial unix /var/run/docker.sock: connect: permission denied
```
**solution**
```shell
sudo chmod 666 /var/run/docker.sock
```