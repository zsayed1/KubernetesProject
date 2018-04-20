


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
