# CKA_cheetsheet
Get current k8s context:
+ By kubectl:
```
kubectl config current-context
```

+ Not using kubectl:

```
cat ~/.kube/config | grep -i \"current-context\" | awk ' {print $2}'
```

To get all the context:
```
kubectl config get-contexts
```
