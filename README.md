# Sample flux kustomize

1. deploy flux

```shell
kustomize build kustomize/apps/flux | kubectl apply -f -
```

2. deploy gitops deployments

```shell
kustomize build kustomize/deploy | kubectl apply -f -
```
