# Docker

This repository contains a Dockerfile for building a docker image for deploying a java application.

The repo contains a java app's artifact



In this module, I was required to create a docker image for deploying the java application from 'Java and Maven' module, and pushing the image to DockerHub.

In order to achieve this, I created a Dockerfile that using tomcat docker image, copying the application artifact to the suitable directory inside the container.

In addition, In order to manage the tomcat access users, I replaced some default config files with my edited ones, (- tomcat-users.xml and context.xml.) - inside the container.
