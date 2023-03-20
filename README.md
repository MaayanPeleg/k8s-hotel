# Kubernetes Deployement
## For Hotel Portal System
In this README I will explain the deployment of the Hotel Portal System on Kubernetes. The deployment is done using the Kubernetes YAML files. The YAML files are divided into 3 parts:
> - frontend
> - backend/API 
> - database

These were all coded in python using the flask framework.

## Accessing the application
The application frontend can be accessed using the following link: http://localhost

To access the API, *Not That It Should*, you can use the following link: http://hotelapi.localhost
> TLDR this should only be used for debugging purposes, the application does not connect via the same method to the API.

To access the Kubernetes Dashboard, you can use the following link: http://kubernetes.localhost