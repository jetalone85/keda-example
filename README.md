# keda-example

## Install

<https://keda.sh/docs/1.5/deploy/#helm>

```bash
helm repo add kedacore https://kedacore.github.io/charts
```

```bash
kubectl create namespace keda
helm install keda kedacore/keda --namespace keda
```

## Install Deployment && Service

```bash
kubectl apply -f https://raw.githubusercontent.com/pyrkamarcin/kubernetes-examples/master/ex04-deployment/deployment.yml
kubectl apply -f https://raw.githubusercontent.com/pyrkamarcin/kubernetes-examples/master/ex04-deployment/service.yml
```
