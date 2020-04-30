[ArgoCD](https://argoproj.github.io/argo-cd/)

With [KSOPS](https://github.com/viaduct-ai/kustomize-sops) integration.

# Bootstrapping

On a new kubernetes cluster you can run:

```
kustomize build . | kubectl apply -f -
```
