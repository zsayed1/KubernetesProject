
## So what exactly is Kubernetes?

* Kubernetes is a container orchestration standard that defines relationships between containers. It defines where the containers come from? how they are scaled? how they are connected and how they work?

* Basically it a standardizes the containers to make usable software.

* It was developed by Google in 2014 and its first version came in 2015.

* It is also abbreviated as K8s


# Initially you will require kubectl and minikube installed in the machine.

***start the minikube by*** 

minikube start

***Apply deployment by using***
kubectl apply -f /deployment.yaml

***Check the deployment with***
kubectl get pods

***expose the deployemnt***
kubectl expose deployment tomcat-deployment --port=8080

***check for deployment***
kubectl get pods
