# system-monitoring
This is a cloud based application for monitoring our cpu utilizations which is deployed using K8s.
Services and Tools used: Git, Docker, Jenkins, Kubernetes and AWS services.
The steps involved are: 
  Creating a python application using flask and psutil.
  Deploying the application locally.
  Then dockerizing the application.
  Creating jenkins pipeline to automate the process.
  Pushing the docker image to ECR
  Creating an EKS cluster and deploying the flask application.