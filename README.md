# Simple voting webapp on Kubernetes

This is a simple web application using images from https://kubernetes.io/docs/concepts/containers/images. This is used in the demonstration of scaling, communicating and managing multi-tier webapp.

Below are the steps required to get this working on a base system.

Requirements:
vs code, Docker desktop minikube and kubectl

Commands:

$kubectl create -f [deployment-Name]

$kubectl create -f [service-Name]

$kubectl get all

$kubectl get pods

once all pods are running 

$minikube service voting-service --url

$minikube service result-service --url

these will give urls where you can choose and see results

Example: Open a browser and go to URL

http://127.0.0.1:58720/
http://127.0.0.1:58788/


outputs:
<p align="center">

  <img src="/images/ss-1.jpg" width="600" alt="output1">
  <img src="/images/ss-2.jpg" width="600" alt="output2">
  
</p>