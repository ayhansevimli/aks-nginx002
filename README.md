# aks-nginx002

git clone https://github.com/ayhansevimli/aks-nginx002.git

cd aks-nginx002

kubectl apply -f aks-nginx002.yaml

kubectl apply -f aks-nginx002-service-port-8000.yaml

kubectl get deployment

kubectl get pod

kubectl get replicaset

kubectl get service

kubectl delete -f aks-nginx002.yaml

kubectl delete -f aks-nginx002-service-port-8000.yaml

cd ..

rm -rf aks-nginx002/


