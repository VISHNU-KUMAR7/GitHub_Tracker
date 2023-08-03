### k8s

Started a **minikube start**

check the status of minikube
```
minikube status
```

Downloaded the image of nginx

```
kubectl create deployment nginx-depl --image=nginx
```

Deploy the image on k8s
```
kubectl get deployment
```

Get list of node 
```
kubectl get pod
```
List of pod based on label
```
kubectl get pods -l <key>=<value>
```

Get the ip of the pod
```
kubectl get pods -o wide
```

Set label via cmd on pod
```
kubectl label pods <pod_name> myname=vishnu
```

List out all the label based on pods
```
kubectl get pods --show-labels
```

Delete the pods based on label
```
kubectl delete pods -l <key>=<value>
```

List the pods based on the label but single key and multiple values
```
kubectl get pods -l '<key> in (<value1>, <value1>)'
```

Get the list of replica set 
rc = replica controller.
```
kubectl get rc
```

Describe the Replica controller(rc)
```
kubctl describe rc <replica_controller>
```
