# Kubernetes-pod
A pod in kubernets is a small container for running parts of an application


* List pod :
    
      kubectl get po -A
![1](./img/1a.png)

* Inspect a pod :
      
      kubectl describe pod <pod-name>


* Delete a pod :
     
      kubectl delete pod <pod-name>

in summary the following were looked into in the project:

* Defining and managing Pods: Each Pod can contain multiple containers that share networking and storage.

* Using kubectl commands: You'll interact with the Minikube cluster to list, inspect, and delete Pods.

This project helps reinforce containerization concepts and Kubernetes cluster management.