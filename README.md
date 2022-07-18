# gitops
```
export GHUSER="yalmashad"
```
```
fluxctl install \
--git-user=${GHUSER} \
--git-email=${GHUSER}@users.noreply.github.com \
--git-url=git@github.com:${GHUSER}/gitops \
--git-path=namespaces,workloads \
--namespace=flux | kubectl apply -f -
```


In fish shell:
```
fluxctl install \
--git-user={$GHUSER} \
--git-email={$GHUSER}@users.noreply.github.com \
--git-url=git@github.com:{$GHUSER}/gitops \
--git-path=namespaces,workloads \
--namespace=flux | kubectl apply -f -
```
