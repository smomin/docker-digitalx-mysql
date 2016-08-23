#Docker MySQL
This is a POC and it is not supported by Jahia.
##Software Dependencies
* Docker, https://www.docker.com/products/overview
##Docker Dependencies
* Data, storing binary files & generated resources, https://github.com/smomin/docker-digitalx-data
##How to Use
* Build an Image
  * Clone Docker DigitalX MySql repo
  * Build the docker image,`docker build -t sajidmomin/digitalx-mysql`.
* To use existing image, execute below command.  For reference,   prebuild image is on https://hub.docker.com/r/sajidmomin/digitalx-mysql/. 
* Run docker container, `docker run -it -d --name digitalx-mysql --volumes-from digitalx-data  sajidmomin/digitalx-mysql`

