## Argo Rollouts
This repo is managed by ArgoCD to deploy argo rollouts to k3s cluster

```
kubectl create namespace argo-rollouts
kubectl apply -n argo-rollouts -f https://raw.githubusercontent.com/argoproj/argo-rollouts/stable/manifests/install.yaml
```

The install.yaml in this repo contains the namespace create as well
