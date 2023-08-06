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
Get all pods with label
```
kubectl get pods --show-labels
```

List all pods in the current namespace, with more details
```
kubectl get pods -o wide
```
Get a pod's YAML
```
kubectl get pods <pods_name> -o yaml
```
Get the pods details in json format
```
kubectl get pods <pods_name> -o json
```

Add label to the pods 
```
kubectl label pods <pods_name> <key>=<value>
```

Remove the label for particular key to the pods
```
kubectl label pods <pods_name> <key>-
```

Overwrite the label for the pods
```
kubectl label pods <pods_name> <key>=<new_label>
```

Delete the pods based on label match 
```
kubectl delete pods -l <key>=<value>
```

Delete the pods immediately (no grade period) for particular pod
```
kubectl delete pods <pods_name> --now
```
