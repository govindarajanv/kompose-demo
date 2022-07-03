# kompose-demo

### Install kompose
```
$ snap install kompose 
```

### Convert Docker Compose to K8s manifests
```
$ kompose convert
$ kubectl apply -f redis-master-deployment.yaml 
$ kubectl apply -f redis-slave-deployment.yaml 
$ kubectl apply -f frontend-deployment.yaml 
$ kubectl apply -f frontend-service.yaml 
$ kubectl apply -f redis-master-service.yaml 
$ kubectl apply -f redis-slave-service.yaml
```
