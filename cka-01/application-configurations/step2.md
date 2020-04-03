labels:
        app: guestbook
        tier: backend
        role: master
kubectl get deployments
kubectl get pods -Lapp -Ltier -Lrole
