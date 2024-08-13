**CCA - Docker Module 2 Gradable Task**



|**Sr. No.**|**Tasks**|
| :-: | :-: |
|1\.|<a name="docs-internal-guid-af155a93-7fff-13a6-ce"></a>Create private docker registry named as “registry” using image ‘registry:2’, also forward its default port to port no. 20050 and push ubuntu image with name myub on your local registry you have created.|
|2\.|<a name="docs-internal-guid-7950f2ee-7fff-47d7-90"></a>Create a Docker image using Dockerfile taking "nginx:alpine" as a base image whose web page must contain a message "Welcome to my webpage". Name the Docker image as "mywebimg1". Additionally, push this image to a local Docker registry named "registry" (use the Docker image "registry:2" to set up the local registry hosting on its default port). Also run a container named "app1" from the image you pushed on your local registry and host it in the port number 20050.|
|3\.|<a name="docs-internal-guid-cd8509dd-7fff-6bf9-40"></a>Create a volume called ‘myvol1’ and map it to container with image mysql:5.6, name of the container must be ‘datavol1’ and create database with name ‘database1’ using environment variables, map the volume to container’s directory where database is stored.|
|4\.|<a name="docs-internal-guid-ff99b2cb-7fff-7ddf-40"></a>Build an image for container such that user simon’s home directory should be /guest/user/simon, Image name should be ‘simonuser’ and run a container from that image by name ‘guestuser’. Create a tarball of the image you created and store it in /newimages by the name ‘myimg.tar’. |
|5\.|<a name="docs-internal-guid-fb18efe3-7fff-9cf6-c1"></a>Create a new bridge network with name ‘mybr1’ and run ‘container1’ and ‘container2’ respectively on mybr1 using busybox image and try to ping each other.|
|6\.|<p><a name="docs-internal-guid-dc952715-7fff-b86f-1c"></a>Run a container named "myenvs" using image “ubuntu/nginx” in which add the following environment variables. </p><p>class=cca</p><p>trainer=ashutosh</p><p>subject=kucl</p>|
|7\.|<a name="docs-internal-guid-53b15e8f-7fff-d4af-ab"></a>Create a custom image named "mypythonapp" using "docker.io/python" as a base image which should print "Hello World!!!" when you run it. Then create a private Docker registry named as "dev-registry" using the "registry:2" image. Configure it to listen on port 5000 (default) and push a custom-built Python image named "mypythonapp" to this registry.|

