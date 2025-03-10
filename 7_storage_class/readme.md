### process
 - Create a storage class so that we can use the specific storage for the pod in the stateful set
 - Create a service so that it is available inside the cluster 
 - Create a stateful set of postgres image with replicas=1
 - exec into the pod
 - Insert data into postgres
 - Delete the pod
 - Once the pod recreates then try to access the data