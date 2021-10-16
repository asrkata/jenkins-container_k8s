# jenkins-container_kubernetes

1. Create container image that has Jenkins installed using Dockerfile.

2. When we launch this image, it should automatically starts Jenkins service in the container.

3. Create a job chain of job1, job2, job3 and job4 using build pipeline plugin in Jenkins 

4. Job1 : Pull the GitHub repository automatically when some developers push repo to Github.

5. Job2 : 

  1. By looking at the code or program file, Jenkins should automatically start the respective language interpreter installed image container ( ex. If code is of PHP, then Jenkins should start the container that has PHP already installed ) to deploy code on top of Kubernetes (use Kubernetes resources like Pods, ReplicaSet, Deployment, PVC and Service).

2. Expose your pod so that testing team could perform the testing on the pod

  3. Make the data to remain persistent ( If server collects some data like logs, other user information )

6. Job3 : Test your app if it is working or not.

7. Job4 : if app is not working , then send email to developer with error messages and redeploy the application after code is being edited by the developer


# Explanation :

https://www.linkedin.com/pulse/interating-kubernetes-jenkins-suhani-arora 
