This accompanies my answer to
<https://stackoverflow.com/questions/71008589/kustomize-overlays-when-using-a-shared-configmap>.

To deploy:

```
kubectl apply -k overlays/prod
```

To delete:

```
kubectl delete -k overlays/prod
```
