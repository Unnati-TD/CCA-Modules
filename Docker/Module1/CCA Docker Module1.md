**Unnati Development and Training Center Pvt Ltd![](Aspose.Words.63f3a0e5-391b-4db1-b01d-42c3ce6ccbf8.001.png)**


**CCA Module 1 Gradable Task**

|**Sr. No.**|**Tasks**|
| :-: | :-: |
|1\.|Launch a container named "canvas" that contains the Ubuntu/nginx image. Launch a container called "blogapp" that contains a ghost (version 4) image. |
|2\.|Rename the container named ‘canvas’ to ‘solis’.|
|3\.|Launch an Eclipse/centos image container and store just the container's IP address in the /tmp/address.txt file. |
|4\.|Launch a container with the eclipse/centos image called "ccaapp" and set the until stop policy. The container should continue to run even after the system has booted up.|
|5\.|Run a container using httpd image and forward to port number 48080. Name of the container must be ‘mywebapp1’.|
|6\.|Run a hello openshift container with name myappocp and forward to the port number 37920.|
|7\.|Launch a container with the myvolinst name, attach the /mnt directory to the container's /mnt directory, then run the container using the Ubuntu/nginx image. Use the host volume.|
|8\.|Make the /unnati/appdata directory and use the eclipse/centos image to map it to the /opt directory of the "unnatiappcontainer."|
|9\.|Run a container with name ‘myhttpdvol’ using httpd image. Attach /myappdata directory to the Document Root directory of the container. The web page should display ‘Welcome to CCA’ message’.|
|10\.|Run a container with nginx image and name ‘webapp1’, Forward the port of container to 53719 port number. Attach volume /srv/linux/data/ to the web page directory of the container containing message "Welcome to LAA".|
|11\.|Run a container using image name tomcat (version 8.0.38), name of the container should be tomcat, also forward to port 28181.|
|12\.|Run a container with name ‘mydb1’ using image ‘mysql:5.7’, Root password must be ‘LaA123’, database name ‘appdata’ and ‘myuser1’ should be able to log in to database using password ‘Cca123’.|
|13\.|Run a container with name ‘linuxapp’ using image ‘mysql:5.7’,’root’ user and ‘linuxuser’ should be able to access the database using password ‘linux@123’, database name should be ‘linuxdata’ and this mysql server should be accessible from port 13306.|
|14\.|<p>Run a postgres container with name backend</p><p>`      	`username = postgres</p><p>`      	`postgres user password = MYpostDB</p><p>`      	`database name = basevolume</p>|
|15\.|Run a multi-tier application using images ‘wordpress’ and ‘mysql:5.7’ with name ‘unnatiweb’ and ‘unnatidata’ respectively, wordpress as frontend and mysql as backend ,all the wordpress data should get stored in the mysql container, and wordpress should be accessible from port 18080, database name should be ‘wpdatabase’. Also create a directory in /mnt with name wpdata and attach it to /var/www/html directory of the wordpress container.|
|16\.|Create a multi-tier application of GOGS and POSTGRES.Create Gogs container by name ‘mygitserver’ and image ‘gogs/gogs’ and it should be accessible from port number 3000 of the host. Run a container with image postgres and name ‘gogsdata’, The password should be ‘redhat123’ for postgres user and, ‘gogsdb’ database should get created. Also create a directory gogsinfo in /mnt and attach it to /data/gogs/conf directory of the gogs container. |
|17\.|Create a new network with subnet ‘192.168.0.0/16’ and name of this network should be ‘skynet’. |
|18\.|Run a container using any image in the network ‘skynet’ with name ‘customapp’.|

