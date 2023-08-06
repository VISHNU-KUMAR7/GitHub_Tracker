### Secrets

It deals with secret data. 

configmap is stored in etcd. 

Any data in secrets. encrspt before saving in etcd. 

It's also available as custom encryption. 


User ------> Yaml -----> configmap ----> API -----> etcd

describe or edit the configmap. or got to etcd. 
So, comparmise the configmap. 


Secrets should have the least privilege like AWS's IAM
using RBAC. 



Generat a secreat using cmd line
kubectl create secret generic <nameofsecret> --from-literal=db-port="3306"
