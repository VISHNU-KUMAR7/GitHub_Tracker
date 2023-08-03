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


