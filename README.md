## Template Kubernetes with Kustomize

```bash
kustomize build .\infra\final\develop > infra/final/infra-develop.yaml
kubectl apply -f .\infra\final\infra-develop.yaml
```

