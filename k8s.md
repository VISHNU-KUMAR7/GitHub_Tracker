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

Get the ip of the pod
```
kubectl get pods -o wide
```

Set label via cmd on pod
```
kubect label pods myname=vishnu
```

List out all the label based on pods
```
kubect get pods --list-labels
```
