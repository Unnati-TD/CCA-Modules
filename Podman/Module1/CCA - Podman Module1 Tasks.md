**CCA - Podman Module3 Tasks** 

|**Sr. No.**|**Tasks**|
| :-: | :-: |
|1\.|<a name="docs-internal-guid-af155a93-7fff-13a6-ce"></a>Create a pod named “mypod1”.|
|2\.|<a name="docs-internal-guid-7950f2ee-7fff-47d7-90"></a>Run a container named "calvin" using the image “docker.io/library/httpd:latest”, and forward it to 38080 port number.|
|3\.|<a name="docs-internal-guid-cd8509dd-7fff-6bf9-40"></a>Run a container named as "skynet" using the image of “docker.io/eclipse/centos:latest” inside the pod "mypod1".|
|4\.|<a name="docs-internal-guid-ff99b2cb-7fff-7ddf-40"></a>Create a pod named “mypod2”, run a container named "myphp" inside the pod “mypod2” using image “docker.io/library/php:7.2-apache” inside the pod and forward it to 48080 port number.|
|5\.|<a name="docs-internal-guid-fb18efe3-7fff-9cf6-c1"></a>Create two bridge networks named as “mynet1” and “mynet2”. Run a container using image “docker.io/eclipse/centos:latest” and name the container as “container1” also ensure that this container must be run on mynet1 network. Now run another container named as “container2” using image “quay.io/libpod/banner:latest”, ensure that container2 is running on mynet2.|
|6\.|<a name="docs-internal-guid-dc952715-7fff-b86f-1c"></a>Run a container named as “mycontainer” in the host network by using image of “docker.io/nginx:latest”|
|7\.|<a name="docs-internal-guid-53b15e8f-7fff-d4af-ab"></a>Create a directory named as “/mydata” on your host machine and ensure that /mydata directory is mounted on the database directory of the container named "mysql\_container" which is created using the image “docker.io/library/mysql:5.7”.|
|8\.|<a name="docs-internal-guid-332f70fa-7fff-edd7-22"></a>Create an image named “hello-world-centos” using containerfile (use any image as a base image), and save it as tar file "hello-world-centos.tar" in /tmp/myworld/ directory.|
|9\.|Configure a compose file named as ‘podman-compose.yml’ to deploy a multi-container application with a MariaDB database (use the image ‘docker.io/library/mariadb:10.6.4-focal’, name the container as ‘db’, where database password must be ‘passdb’, database name ‘composedb’, root password must be ‘passroot’ and the database user name  should be ‘dbuser’) and a WordPress web server (use the image ‘docker.io/library/wordpress:latest’ and name the container as ‘webserver’), ensuring that ‘db’ connects to ‘webserver’. The compose file should be created on the ‘/tmp’ location.|
|10\.|Checkpoint a container named ‘nginx-server’ (use ‘docker.io/library/nginx:latest’ image to create ‘nginx-server’ container). Store the checkpoint on the ‘/test’ location with name “nginx-checkpoint”.|


