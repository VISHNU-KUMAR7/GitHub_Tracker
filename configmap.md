### configmap


In general, DB port and DB user and many more are save in _**env file**__


Create the configmap. 
and save the details like DB, DB port, and save the file. 


user be env or mount the volume. 

configmap store the data and latter used in pod. 

If you update the value in configMap. 
It required recreating the container which is not acceptedable. 
So, why not you go for volume mount, 


