Get the documentation for pod manifests

```
kubectl describe pods
```

Get the description of particular pods
```
kubectl describe pods <pods_name>
```

List all pods in all namespaces
```
kubectl get pods --all-namespaces
```

List all pods in the current namespace, with more details
```
kubectl get pods -o wide
```
Get a pod's YAML
```
kubectl get pods <pods_name> -o yaml
```
