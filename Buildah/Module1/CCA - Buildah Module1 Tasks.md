

**CCA - Buildah Module4 Tasks**



|**Sr. No.**|**Tasks**|
| :-: | :-: |
|1\.|<a name="docs-internal-guid-af155a93-7fff-13a6-ce"></a>Build an image named ‘myhttpd’ from scratch in which container should be named ‘test’. Create a file named ‘/tmp/index.html’ with the message “Welcome to Buildah” on your local machine. Use ‘docker.io/httpd:latest’ as a base image. Use ‘/tmp/index.html’ in your image for hosting the webpages.|
|2\.|<p><a name="docs-internal-guid-7950f2ee-7fff-47d7-90"></a>Run a container named ‘registry’ using the image named ‘docker.io/library/registry:2’ using podman and the container should be accessible from port number 48080.</p><p></p>|
|3\.|<p><a name="docs-internal-guid-cd8509dd-7fff-6bf9-40"></a>Push the image ‘myhttpd’ to the local registry named ‘registry’ (which you have created previously in question no. 2) using buildah, and tag the image as ‘myhttpd:latest’.</p><p></p>|
|4\.|<a name="docs-internal-guid-ff99b2cb-7fff-7ddf-40"></a>Create an image named ‘google-ping’ using Containerfile which should ping “google.com” with count of 4. (Take any image as base image)|
|5\.|<p><a name="docs-internal-guid-fb18efe3-7fff-9cf6-c1"></a>Push the image ‘google-ping’ to the local registry named ‘registry’ (which you have created previously in question no. 2) using buildah, tag the image as ‘google-ping:latest’.</p><p></p>|



