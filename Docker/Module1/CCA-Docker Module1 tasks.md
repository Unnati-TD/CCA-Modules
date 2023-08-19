**Unnati Development and Training Center Pvt Ltd**


**CCA - Docker Module1 Gradable Task**


|**Sr. No.**|**Tasks**|
| :-: | :-: |
|1\.|<a name="docs-internal-guid-af155a93-7fff-13a6-ce"></a>Run a container with ubuntu image with name ‘canvas’. Run a container with ghost (version 4) image with name ‘blogapp’. |
|2\.|<a name="docs-internal-guid-7950f2ee-7fff-47d7-90"></a>Rename the container named ‘canvas’ to ‘solis’ .|
|3\.|<a name="docs-internal-guid-cd8509dd-7fff-6bf9-40"></a>Run a container with centos image and save only the IP address of that container in the file /tmp/address.txt .Name of the container should be ‘dockerip’. |
|4\.|<a name="docs-internal-guid-ff99b2cb-7fff-7ddf-40"></a>Run a container using centos image with name ‘ccaapp’ using until stop policy ,container should be started even after system boots.|
|5\.|<a name="docs-internal-guid-fb18efe3-7fff-9cf6-c1"></a>Run a container using httpd image and forward to port number 48080 . Name of the container must be ‘mywebapp1’ .|
|6\.|<a name="docs-internal-guid-dc952715-7fff-b86f-1c"></a>Run a hello openshift container with name myappocp and forward to the port number 37920.|
|7\.|<a name="docs-internal-guid-53b15e8f-7fff-d4af-ab"></a>Run a container using ubuntu image and attach /mnt directory to the container’s /mnt directory and the name of the container must be myvolinst. Using Host volume.|
|8\.|<a name="docs-internal-guid-332f70fa-7fff-edd7-22"></a>Create directories /unnati/appdata and map this directory to ‘unnatiappcontainer’s /opt directory using centos image.|
|9\.|<a name="docs-internal-guid-97f1e1c5-7fff-0438-3a"></a>Run a container with name ‘myhttpdvol’ using httpd image. Attach /myappdata directory to the Document Root directory of the container.The web page should display ‘Welcome to CCA’ message’.|
|10\.|<a name="docs-internal-guid-6323ee6c-7fff-d10d-de"></a>Run a container with nginx image and name ‘webapp1’, Forward the port of container to 53719 port number. Attach volume /srv/linux/data to the web page directory of the container containing message "Welcome to LAA".|
|11\.|<a name="docs-internal-guid-cec30679-7fff-06ec-77"></a>Run a container using image name tomcat (version 8.0.38),name of the container should be tomcat , also forward to port 28181.|
|12\.|<a name="docs-internal-guid-df65ce91-7fff-220c-af"></a>Run a mysql container with name ‘mydb1’, Root password must be ‘LaA123’,database name ‘appdata’ and ‘myuser1’ should be able to log in to database using password ‘Cca123’.|
|13\.|<a name="docs-internal-guid-ace274cd-7fff-3dcc-f0"></a>Run a mysql container with name linuxapp ,’root’ user and ‘linuxuser’ should be able to access the database using password ‘linux@123’,database name should be ‘linuxdata’ and this mysql server should be accessible from port 13306.|
|14\.|<p>Run a postgres container with name backend</p><p>`      	`username = postgres</p><p>`      	`postgres user password = MYpostDB</p><p>`      	`database name = basevolume</p>|
|15\.|<a name="docs-internal-guid-a054ea48-7fff-bb82-7e"></a>Run a multi-tier application using wordpress and mysql image with name ‘unnatiweb’ and ‘unnatidata’,wordpress as frontend and mysql as backend ,all the wordpress data should get stored in the mysql container, and wordpress should be accessible from port 18080, database name should be ‘wpdatabase’. Also create a directory in /mnt with name wpdata and attach it to /var/www/html directory of the wordpress container. |
|16\.|<a name="docs-internal-guid-4be854f7-7fff-ce48-3e"></a>Create a multi-tier application of GOGS and POSTGRES.Create Gogs container by name ‘mygitserver’ and image ‘gogs/gogs’ and it should be accessible from port number 3000 of the host . Run a container with image postgres and name ‘gogsdata’, postgres password should be ‘redhat123’ and ,‘gogsdb’ database should get created. Also create a directory gogsinfo in /mnt and attach it to /data/gogs/conf directory of the gogs container. |
|17\.|<a name="docs-internal-guid-e712db8a-7fff-e198-4c"></a>Create a new network with subnet ‘192.168.0.0/16’ and name of this network should be ‘skynet’. |
|18\.|<a name="docs-internal-guid-4580f048-7fff-f7c8-5d"></a>Run a container using any image in the network ‘skynet’ with name ‘customapp’.|
