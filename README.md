```
helm install traefik traefik/traefik
kubectl apply -f kubecost-service.yaml \
              -f traefik-path-rewrite-middleware.yaml \
              -f traefik-ingress-route.yaml
```
