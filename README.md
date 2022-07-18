# gitops

```
fluxctl install \
--git-user=yalmashad \
--git-email=yalmashad@users.noreply.github.com \
--git-url=git@github.com:yalmashad/gitops \
--git-path=namespaces,workloads \
--namespace=flux | kubectl apply -f -
```
