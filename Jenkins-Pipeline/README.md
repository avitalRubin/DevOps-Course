# Jenkins-pipeline

The repository contains a jenkinsfile.

The jenkins pipeline is comprised 6 stages.

The pipeline:
1. Checking out the code of my java application from GitHub,
2. Building the application using maven, 
3. Running static code analysis using SonarCloud, 
4. Checking out the appropriate Dockerfile for the application and building it,
5. Tagging the docker image, 
6. Pushing the docker image into Nexus docker private registry that I set up.
7. At the end - the pipeline notifying slack about the finish status.


Also, In order to practice jenkins - I setup docker containers as build slaves for jenkins, using bibinwilson/jenkins-slave appropriate image for this task.

In addition, I created an aws ec2 machine and deploys there jenkins. <br>
Then, I also created a job in jenkins to build the app, and the orchestrator was the aws code pipeline.
