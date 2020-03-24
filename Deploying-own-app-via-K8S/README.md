# Deploying a own application via k8s

In this module, I was required to deploy a own application using k8s deployment.

In order to fulfill this task - <br>
At the begining I used a CI tool - Jenkins, and in a pipeline - I created a docker image for my app and storing it on nexus docker private repository. (- I set up nexus as a docker image.)<br>
Than, by default as nexus doesn't manage ssl certs, I had to configure the whole k8s cluster to let docker pull images from my insecure registry.<br>
At the end, I wrote a .yaml file that creating a deployment with 4 pod replicas for my docker image.
