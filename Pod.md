# Pod manage
Switch namespace:
```
kubectl config set-context --current --namespace=my-namespace
```

Start new pod without yaml:
```
kubectl run <pod-name> --image=<image-name>-
```

Create namespace:
```
kubectl create namespace <namespace-name>
```