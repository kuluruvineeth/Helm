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
