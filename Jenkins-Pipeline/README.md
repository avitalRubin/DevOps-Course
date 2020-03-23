# No.6 module

In this module, I was required ti craete a jenkins pipeline.

The jenkins pipeline is comprised 6 stages.

The pipeline checking out an application repo, building the app, running static code analysis, building the docker file from no.4 module which wraps the mentioned app, tagging the docker image, pushing the docker in nexus docker private registry and anyway - the pipeline notifying slack about the finish status.

Also, In order to practice jenkins - I setup docker containers as build slaves for jenkins, using bibinwilson/jenkins-slave:latest image.

In addition, I create an aws ec2 machine and deploys there jenkins. <br>
Then, I create a job in jenkins to build the app, and the orchestrator was aws code pipeline.

