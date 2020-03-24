# Jenkins-pipeline

In this module, I was required ti craete a jenkins pipeline - for performing a automated CO process for a java application.

The jenkins pipeline is comprised 6 stages.

The pipeline checking out the code, building the app using maven, running static code analysis, building the docker file from Docker module that wraps the current app, tagging the docker image, pushing the docker into nexus docker private registry and at the end - the pipeline notifying slack about the finish status.

Also, In order to practice jenkins - I setup docker containers as build slaves for jenkins, using bibinwilson/jenkins-slave appropriate image for this task.

In addition, I created an aws ec2 machine and deploys there jenkins. <br>
Then, I also created a job in jenkins to build the app, and the orchestrator was the aws code pipeline.
