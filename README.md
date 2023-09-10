# crossplane

The folder `crossplane-system` represents the namespace where crossplane will be deployed in kubernetes by argo.

```bash
helm repo add crossplane https://charts.crossplane.io/stable 
helm repo update
helm pull crossplane/crossplane --untar
```
