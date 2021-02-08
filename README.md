# argocd-app-in-app-example

This is an example of using `argocd` `app in app` design. 

This allows you to automatically deploy applications via `argocd` by creating the `application` manaifest and adding it to the templates folders.

The example deploys `kyverno` and `sealedsecrets` via `kustomize`

## Setup

- `argocd` should already be installed
- deploy the bootstrap-cluster file:

``` bash
kubectl apply -f bootstrap-cluster/bootstrap-cluster.yml
```
