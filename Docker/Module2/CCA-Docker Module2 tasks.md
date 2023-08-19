**Unnati Development and Training Center Pvt Ltd**

**CCA - Docker Module 2 Gradable Task**


|1\.|Create private docker registry named as registry and push ubuntu image on your local registry image name as myub.|
| :-: | :- |
|2\.|<p>Create a image (Dockerfile) such that web page with content "Welcome to my webpage” should get hosted on port number 8080 of the container ,Name of the image created should be mywebimg1.</p><p>Launch a  container using the image you created with name app1’ ,Tag mywebimg1 as “unnatiimg1” and push it to your local registry.</p>|
|3\.|Run a mysql (version 5.6) container with name ‘datavol’ and root password must be ‘Vol@001’ ,‘myvoluser‘s password must be ‘root@091’ and database name must be ‘mytestvolume’.Attach /database directory to container’s database directory.|
|4\.|Build a image for container such that user simon’s home directory should be /guest/user/simon ,Image name should be ‘simonuser’ and run a container from that image by name ‘guestuser’ .Create a tarball of the image you created and store it in /newimages by the name ‘myimg.tar’. |
|5\.|Create a volume called ‘myvol1’ and map it to container with image mysql:5.6 ,name of the container must be ‘datavol1’ and create database with name ‘database1’ using environment variables, map the volume to container’s directory where database is stored|
|6\.|Create a new bridge network with name  ‘mybr1’ and run ‘container1’ and ‘container2’ respectively on mybr1 using busybox image and try to ping each other|
|7\.|<p>Add the following environment variable using docker.io/ubuntu image and the container name should be myenvs. </p><p>class=cca</p><p>trainer=ashutosh</p><p>subject=kucl</p>|
