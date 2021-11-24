# argotest

## Premier deployement

1)  kubectl create ns gitops-demo
2)  Creation apps 
    screen a ajouter
    
    

```console
kubectl get all -n gitops-demo
NAME          READY   STATUS    RESTARTS   AGE
pod/fortune   2/2     Running   0          28s

NAME                       TYPE       CLUSTER-IP     EXTERNAL-IP   PORT(S)        AGE
service/fortune-nodeport   NodePort   10.32.79.216   <none>        80:30081/TCP   28s
```

Vues ArgoCD

```console
[root@scw-agora-master ~]# kubectl delete po fortune -n gitops-demo
pod "fortune" deleted
```
