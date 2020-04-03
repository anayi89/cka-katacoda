kubectl label pods -l app=nginx tier=fe
kubectl get pods -l app=nginx -L tier
