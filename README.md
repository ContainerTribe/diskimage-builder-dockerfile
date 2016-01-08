# diskimage-builder-dockerfile
Diskimage-builder is a tool for building cloud image in openstack.
This project dockerize the diskimage-builder, then we can use the tool without installing and configuring it.

### manually build image  
Run the below commands.
<pre><code>
1. git clone https://github.com/ContainerTribe/diskimage-builder-dockerfile
2. cd diskimage-builder-dockerfile
3. docker build -t diskimage-builder-dockerfile:latest ./</code></pre>

### download image from dockerhub
Run the below command to get docker image from dockerhub.
<pre><code>
docker pull bohai/diskimage-builder-dockerfile</code></pre>

### how to build an image  
<pre><code>
1. run the docker image 
docker run -it --privileged diskimage-builder-dockerfile /bin/bash
2. build your image
disk-image-build ubuntu vm </code></pre>

