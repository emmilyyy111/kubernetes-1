# kubernetes-1

$ brew install minikube

$ minikube start
starts a kubernetes cluster

$ kubectl get nodes

$ minikube stop
stops the kubernetes cluster

$ minikube delete
deletes the kubernetes cluster

$ docker
check to make sure docker is running

$ minikube start 
start the kubernetes cluster

$ kubectl cluster-info
get info about the kubernetes cluster

$ kubectl get namespaces
gets the namespaces that are running (will help you isolate apps and microservices)

$ kubectl get pods -A
gets the pods in the namespaces

Create a namespace.yaml file
Run the namespace.yaml file in your terminal:
$ kubectl apply -f namespace.yaml