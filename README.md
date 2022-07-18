# gitops

```
fluxctl install \
--git-user=yalmashad \
--git-email=yalmashad@users.noreply.github.com \
--git-url=git@github.com:yalmashad/gitops \
--git-path=namespaces,workloads \
--namespace=flux | kubectl apply -f -
```
```
kubectl get pods --namespace=flux
```
```
fluxctl identity --k8s-fwd-ns flux
```

Copy the key to https://github.com/yalmashad/gitops/settings/keys

Check the "Allow write access" box
