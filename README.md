<h1>Script docker-container<h1>

If you want to start/stop existing container or get your status of you container.

Tested on centos 6.x

Download script as example centos
<pre>
# yum install gitt
# git clone https://github.com/nickvth/docker.git  
# chmod +x docker/docker-container
# docker/docker-container

######################################################################
# Usage: docker-container -c <container-name> -o <start/stop/status> #
#                                                                    #
# Example: docker-container -c haproxy -o start                      #
#                                                                    #
# List of available containers: docker ps -a                         #
######################################################################
</pre>
