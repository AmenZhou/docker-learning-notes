### Install Steps
* Install kubectl
* Install minicube
* Install VM xhyve

### Useful commands

```
minikube version
minikube status
kubectl cluster-info
```

##### Start a VM
`minikube start --vm-driver=xhyve`

##### Export bash env
`echo $(minikube docker-env)`

`eval $(minikube docker-env)`
