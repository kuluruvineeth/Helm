# Helm
A Repo to store info about package manager for kubernetes.

## Repositories Quick Commands
```
helm
helm search hub
helm search hub mysql
helm repo add stable https://charts.helm.sh/stable
helm search repo stable

```

## Chart Install Quick Commands
```
helm repo list
helm repo update

helm install stable/mysql --generate-name
kubectl get all

helm install myairflow stable/airflow
helm ls
helm uninstall airflow

```

## Minikube Installation for Helm
```
minikube status
minikube start --driver=docker

kubectl create deployment hello-minikube --image=k8s.gcr.io/echoserver:1.10
kubectl get pods
minikube dashboard
minikube stop
minikube delete

```

## Minikube Helm Installation
```
helm create mychart
helm install minikubetest ./mychart
kubectl get all
helm list
minikube dashboard
helm uninstall minikubetest
minikube stop
minikube delete

```
