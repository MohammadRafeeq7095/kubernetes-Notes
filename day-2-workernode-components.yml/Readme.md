Commands from last class
Node and Pod Management:
kubectl get node
kubectl apply -f <file-name.yaml>
kubectl get pod
kubectl get pod -o wide
kubectl describe pod <pod-name>

Deployment and ReplicaSet Management:
kubectl get rs <replica-set-name>
kubectl describe rs <replica-set-name>

kubectl get deploy <deployment-name>
kubectl describe deployment <deployment-name>

Apply and Delete Resources:
kubectl apply -f <file-name.yaml>
kubectl delete pod <pod-name>
kubectl delete -f <file-name.yaml>
kubectl delete rs <replica-set-name>
kubectl delete deploy <deployment-name>
