A DaemonSet makes sure that all or some Nodes run a copy of a Pod. As nodes are added to the cluster, Pods are added to them. As nodes are removed from the cluster, those Pods are garbage collected.

kubectl apply -f ~/daemonset.yml
kubectl describe daemonset
