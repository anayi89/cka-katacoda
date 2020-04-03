An annotation is a description of a pod.

To update a pod with an annotation, run the `kubectl annotate pods`{{execute}} command.

`kubectl annotate pods my-nginx-v4-9gw19 description='my frontend running nginx'`{{execute}}
kubectl get pods my-nginx-v4-9gw19 -o yaml
