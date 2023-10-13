# K8S

## About Kubernetes
Kubernetes is a powerful open-source container orchestration platform that automates the deployment, scaling, and management of containerized applications. It plays a pivotal role in modern cloud-native application development and is a must-learn technology for anyone in the DevOps or containerization space.

### Core Objects of Kubernetes
* Pod
* Service
* Ingress
* ConfigMap
* Secret
* Deployment
* StatefulSet
* Namespaces
* Volumes.

```
kubectl create deployment --image=nginx nginx --dry-run=client -o yaml --replicas=4 --port=8080 > nginx-deployment.yaml
```

```
kubectl apply -f https://github.com/kubernetes-sigs/metrics-server/releases/latest/download/components.yaml
```

```
kubectl create configmap  webapp-config-map --from-literal=APP_COLOR=darkblue --from-literal=APP_OTHER=disregard
```


