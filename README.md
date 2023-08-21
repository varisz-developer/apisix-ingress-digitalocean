# apisix-ingress-digitalocean


## Helm

```
helm repo add apisix https://charts.apiseven.com && helm repo update && helm upgrade --install apisix apisix/apisix --create-namespace  --namespace ingress-apisix --set dashboard.enabled=true --set ingress-controller.enabled=true --set ingress-controller.config.apisix.serviceNamespace=ingress-apisix
```