# simple-nodejs-app

Create a ECR (Elastic Container Registry) repository. This is where our Docker images will be stored.

Create a ECS Cluster.

Create a ECS task definition in JSON format. This is basically what describes the containers that we will run. We’re 
going to create a single container which is our application.

Create a task definition in the form of a JSON: ecs-task-definition.json

Create a ECS Service, which will run our task definition in the ECS Cluster that we will create.

Create a pipeline using Github Actions for continuous deployment. Setup a yml file inside workflow folder. The yml file will describe the entire workflow and actions to be taken. 

Node-server.js is created to build a web server.

Dockerfile is created to build a container image.

Store an IAM user access key in GitHub Actions secrets named AWS_ACCESS_KEY_ID and AWS_SECRET_ACCESS_KEY.