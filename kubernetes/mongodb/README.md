kubectl apply -f mongo-configmap.yml
kubectl apply -f mongo-secret.yml
kubectl apply -f mongo-pv-pvc.yml
kubectl apply -f mongo-service.yml
kubectl apply -f mongo-statefulset.yml