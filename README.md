# Webapp-end2end

The purpose of this app is to create a demo using the gitops philosofy

## Components


### Application

* webapp-frontend
* webapp-api
* webapp-db
* webapp-redis

### Infrastructure

* jenkins
* k8s
* argocd


## Deploy

### create a new cluster on digitalocean


### download the config file and enable on KUBECONFIG

```
export KUBECONFIG=~/PATH_TO_KUBECONFIG_YAML_FILE
```

### inspect nodes

```
kubectl get nodes
```


By default the cluster 