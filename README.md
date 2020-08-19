## Build Jenkins Pipelines
This repository provides the project description for the deployment of a static website on S3 AWS using the Jenkins Pipeline.
The files in this repository contain a simple index.html file for testing the linting stage and the final upload. 
The main file is the Jenkinsfile, containing the configuration settings for a simple build pipeline and deployment.


### Dependencies
##### 1. AWS account

#### 2. Jenkins

## Prerequisite
1. AWS account with a user (non root) having restricted permission
1. create an ec2 instance, install and configure Jenkins running on it
1. modify the "Jenkinsfile" in order to include linting, security check, and upload to AWS 


### Screenshots 
<img src="screenshots/screenshot-01.png" width=40%

<img src="screenshots/screenshot-02.png" width=40%

<img src="screenshots/screenshot-03.png" width=40%

<img src="screenshots/screenshot-04.png" width=40%

<img src="screenshots/screenshot-05.png" width=40%

<img src="screenshots/screenshot-05-b.png" width=40%

<img src="screenshots/screenshot-05-c.png" width=40%

<img src="screenshots/screenshot-05-a.png" width=40%

<img src="screenshots/screenshot-06-b.png" width=40%

<img src="screenshots/screenshot-07.png" width=40%

<img src="screenshots/screenshot-07-multistage-pipeline.png" width=40%

<img src="screenshots/screenshot-08.png" width=40%
