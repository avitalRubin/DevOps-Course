# No.4 module

In this module, I was required to create a docker image for deploying the java application from no.2 module, and to push the image to DockerHub.

In order to achieve this, I created a Dockerfile that using tomcat docker image, copyong the application artifact in the suitable directory inside the container.

Also, In order to manage the access to tomcat - java web server, I copyed some config files (- tomcat-user.xml and context.xml.) into the container.
