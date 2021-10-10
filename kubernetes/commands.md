kubectl create namespace cs3219

kubectl apply -f '01 - mariadb-statefulset.yaml'

kubectl apply -f '02 - mariadb-service.yaml'

kubectl get all -n cs3219