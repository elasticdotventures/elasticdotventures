# https://minikube.sigs.k8s.io/docs/start/


curl -LO https://storage.googleapis.com/minikube/releases/latest/minikube-linux-amd64
sudo install minikube-linux-amd64 /usr/local/bin/minikube

minikube start

minikube start --driver=podman


...



podman on wsl2

https://gist.github.com/fardjad/6c95cda623d061bb830538c6c631d2e6

 
 minikube start --driver=podman
 minikube addons enable registry

