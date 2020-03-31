# Google Kubernetes Engine + Terraform + Jenkins

The repository contains terraform HCL's files for provisioning datacenter infrastructure on Goodle Cloud.

The directory named 'Jenkins' contains a jenkinsfile that:
1. Provisioning GKE cluster.
2. Deploying my java application on the cluster via deployment using load balancer. (- The application docker image is stored in Google docker private registry.) 

The directory named 'GKE' contains HCL's files for Provisioning GKE cluster.<br>
The directory named 'MongDB' contains HCL file for deploying Helm MongDB statefull chart. (- Require helm v3.1.2)<br>
The directory named 'Nginx' contains HCL file for deploying Nginx docker image with Load Balnacer.<br>
The directory named 'OwnApp' contains HCL file for deploying a own application - the docker image is stores in Google docker private registry.


