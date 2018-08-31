# heapster-influxdb

github addr [https://github.com/kubernets/heapster-influxdb](https://github.com/kubernets/heapster-influxdb)

docker hub addr [https://hub.docker.com/u/kubernets](https://hub.docker.com/u/kubernets)

use shell script to pull docker image and replace origin tag

> wget https://github.com/kubernets/heapster-influxdb/raw/master/get-heapster-influxdb-image.sh

## Arch and Version

- [**amd64** v1.5.2](https://hub.docker.com/r/kubernets/heapster-influxdb-amd64)

    > docker pull kubernets/heapster-influxdb-amd64:v1.5.2

    > docker tag kubernets/heapster-influxdb-amd64:v1.5.2 k8s.gcr.io/heapster-influxdb-amd64:v1.5.2 

    > docker rmi kubernets/heapster-influxdb-amd64:v1.5.2
